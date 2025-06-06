## **NOTE**
- Every heading inside your html file has a by default margin of `1em` assigned to that.

- Even if we give 0 margin to any html element , even then they will not collide with other html element.
    - WHY?? 
        - jab do adjacent html elements ko margin provide kiya jata hai to vertical direction unka margin add nhi 
        hota bulki dono element me se jika margin bada hai wo margin vertical direction me apply ho jata hai.
- There are two types of measurement unit (https://blog.logrocket.com/using-em-vs-rem-css/)
    1. em
    2. rem

## **Media Queries**
- Responsive web pages means for different types of screen, you are going to get different types of css style.
- There is the concept of `mobile first development` which says that we need to do the development considering mobile screen first and then should expand it to other types of screen.
- To make responsive web pages we use `media queries`.
- Ex:
    ```
        @media (min-width: 600px){
            nav li:firstchild{
                flex-basis:auto;
                flex-grow:1;
            }
        }
    ```
#### **UNICODE**
- https://medium.com/@eokinch/unicode-characters-in-html-css-a55c77fd3570
