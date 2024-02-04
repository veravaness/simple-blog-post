# simple-blog-post


:0
1
class BlogPost {
2
  String title;
3
  String content;
4
  String author;
5
​
6
  BlogPost(this.title, this.content, this.author);
7
​
8
  void editPost(String newTitle, String newContent) {
9
    title = newTitle;
10
    content = newContent;
11
  }
12
​
13
  void displayPost() {
14
    print('Title: $title');
15
    print('Author: $author');
16
    print('Content: $content');
17
  }
18
}
19
​
20
void main() {
21
  // Example usage
22
  BlogPost myPost = BlogPost('nigeria situation', 'nigeria is going through a lot right now.', 'vera vanessa');
23
  myPost.displayPost();
24
​
25
  // Editing the post
26
  myPost.editPost('nigeria and angola afcon match', 'nigeria won angola with 1:0.');
27
  myPost.displayPost();
28
}
Console
Title: nigeria situation
Author: vera vanessa
Content: nigeria is going through a lot right now.
Title: nigeria and angola afcon match
Author: vera vanessa
Content: nigeria won angola with 1:0
