!DOCTYPE: html;
html:
  .lang: "en";
  head:
    title: "This is a title.";
    link:
      .rel: "stylesheet";
      .href: "styles.css";
    ;
  ;
  body:
    h1: "This is a heading";
    input:
      .type: "password";
      .placeholder: "Input field";
    ;
    br;
    input:
      .placeholder: "Read only";
      .readonly;
    ;
    br;
    p: "Here, it is only " 
      span: "3"
        .id: "span";
      ;
      " days old."
    ;
    button: "This is a button with a unique ID."
      .id: "btn";
    ;
  ;
  script:
    .src: "script.js";
  ;
;
