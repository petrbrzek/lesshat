### <a name="user-select"></a> &#8226; user-select
**Summary:**

Translates the element by the given amount along the Z axis.

Resources: **[MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/user-select)**

**Syntax:**
  
  Default value: auto

    .user-select(none | text | all | element)

**Example:**

    div {
     .user-select(none);
    }
    
    // Result
    div {
     -webkit-user-select: none;
     -moz-user-select: none;
     -ms-user-select: none;
     user-select: none;
    }