!DOCTYPE: html;
html:
  .attributes:
    lang: "en";
  ;
head:
  title: "This is a title.";
  link:
    .attributes:
      rel: "stylesheet";
      href: "styles.css";
    ;
  ;
;
body:
  h1: "This is a heading";
  input:
    .attributes:
       type: "password";
       placeholder: "Input field";
    ;
  ;
  br;
  input:
    .attributes:
       placeholder: "Read only";
       readonly;
    ;
  ;
  br;
  p: "Here, it is only " span: 3; " days old.";
  button: "This is a button with a unique ID."
    .attributes:
      id: "btn";
    ;
  ;
;
;
