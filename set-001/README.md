# Mock Frontend Interview Question - Set 1

## 1. Trivia

### 1.1 Explain CSS box Model

<details>
  <summary>View answer</summary>
  
  ### 
  * The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content.
  * It is important to understand that the <strong>width</strong> and <strong>height</strong> properties you set on an element do not include padding, borders, or margins! It only sets the width and height of the content area.
  * This default behaviour can be changed by the `box-sizing` property
    * By default `box-sizing` property is set to the value `content-box` which means the padding and border are not included in width and height of the element. Therefore the height and width is decided by content.
    * We can set `box-sizing: border-box` which will make sure that padding and border are included in the width and height of the element.
      * This is the standard property used by many css libraries to create a consistent behaviour for all the elements.
      ```
      * {
        box-sizing: border-box;
      }
      ```
  * [Code demonstration](001/css-box-model.html)
</details>
