# Javaチートシート

- フォルダ内の更新日付が最新のファイルを取得

  ``` java
  String fileSaveUrl = "検索したいフォルダ";
  File file = Files.list(Paths.get(fileSaveUrl))
      .sorted((p1, p2) -> {
          try {
              return Files.getLastModifiedTime(p2)
                  .compareTo(Files.getLastModifiedTime(p1));
          } catch (IOException e) {
              throw new RuntimeException(e);
          }
      })
      .findFirst().get().toFile();
  ```
