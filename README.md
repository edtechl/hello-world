# hello-world
GitHub practice

class Ed() implements HelloWorld {

  int age = 18;

  public static void __construct(String me) {
    this.me = me;
  }

  public void makeCommit(String contents) {
    contents = proofread(contents);
  }

  public String proofread(String contents) {
    return contents + "\nIt's all good :)";
  }

}
