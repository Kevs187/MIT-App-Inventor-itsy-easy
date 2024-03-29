[[Table of Contents](Index.md#tblcontents)]

# Chapter 2

### Basic Layout

One of the main reason, why should need to learn about basic layout, is because we need to understand the proper layout for the best of **User Experience** (known as **UX**) and giving some better alignment of your **User Interfaces**.

In **MIT App Inventor** they have 5 types of Layout components.

  * Vertical Arrangement
  * Horizontal Arrangement
  * Vertical Scroll Arrangement
  * Horizontal Scroll Arrangement
  * Table Arrangement

---

### Vertical Arrangement

The uses of **Vertical Arrangement** is to align all the **User Interfaces** vertically.

* **Step [0]**

    ![Vertical-Arrangement-00.png](assets//Chapter-2//Vertical-Arrangement-00.png)

    > Navigate the [Pallete Panel](assets//Common//Pallete-Panel.png) and click the **Layout** tab.

    ![Vertical-Arrangement-01.png](assets//Chapter-2//Vertical-Arrangement-01.png)

    > Then once you click the **Layout** tab, find the **Vertical Arrangement** component.

    ![Vertical-Arrangement-02.png](assets//Chapter-2//Vertical-Arrangement-02.png)
    
    > and when you find it, drag it and drop it... at the [Designer Viewer](assets//Common//Designer-Viewer.png).

* **Step [1]**

    ![Vertical-Arrangement-10.png](assets//Chapter-2//Vertical-Arrangement-10.png)

    > Next... navigate the [Pallete Panel](assets//Common//Pallete-Panel.png) again and click the **User Interface** tab.

    ![Vertical-Arrangement-11.png](assets//Chapter-2//Vertical-Arrangement-11.png)
    ![Vertical-Arrangement-12.png](assets//Chapter-2//Vertical-Arrangement-12.png)

    > Find the **Button** component drag it and drop it inside of **Vertical Arrangement** (Actually... i put a 3 buttons inside on it), and see what happen, all buttons that i put in... was align vertically.
    > 
    > #### Take Note :
    > 
    > * **Note [0]** : Not just a button user interface could be align vertically, although the other user interfaces too... like (Label, Checkbox, Switch, Textbox, etc...).
    >
    > * **Note [1]** : If you change the width of **Vertical Arrangement** as **Fill Parent**, it would be fit onto your screen width [(see the image)](assets//Common//Fill-parent.png).
    >
    > * **Note [2]** : You can add background color in **Vertical Arrangement**.
    >
    > * **Note [3]** : You can put all the widgets from the center horizontally, by change it the **AlignHorizontal** property from **Left** to **Center**  [(see the image)](assets//Common//AlignHorizontal-Center.png).

---

### Horizontal Arrangement

The purpose of using **Horizontal Arrangement** is to align all the **User Interface** horizontally, same as on **Vertical Arrangement**, although in the opposite direction.

* **Step [0]**

    ![Horizontal-Arrangement-00.png](assets//Chapter-2//Horizontal-Arrangement-00.png)

    > Go to [Pallete Panel](assets//Common//Pallete-Panel.png) click the **Layout** tab.

    ![Horizontal-Arrangement-01.png](assets//Chapter-2//Horizontal-Arrangement-01.png)
    ![Horizontal-Arrangement-02.png](assets//Chapter-2//Horizontal-Arrangement-02.png)

    > Find the **Horizontal Arrangement** and then drag it and drop it on [Designer Viewer](assets//Common//Designer-Viewer.png).

* **Step [1]**

    ![Horizontal-Arrangement-10.png](assets//Chapter-2//Horizontal-Arrangement-10.png)
    ![Horizontal-Arrangement-11.png](assets//Chapter-2//Horizontal-Arrangement-11.png)
    ![Horizontal-Arrangement-12.png](assets//Chapter-2//Horizontal-Arrangement-12.png)
    ![Horizontal-Arrangement-13.png](assets//Chapter-2//Horizontal-Arrangement-13.png)

    > Go back again in [Pallete Panel](assets//Common//Pallete-Panel.png) click the **User Interface** tab, Drag 3 buttons and put it inside on **Horizontal Arrangement**, click the **Horizontal Arrangement** at the [Components Panel](assets//Common//Components-Panel.png), and then change all 3 buttons width from **Automatic** to **Fill Parent**, and you'll see what happen, all 3 buttons width are equal to each other.
    >
    > #### Take Note :
    > 
    > * **Note [0]** : Could i add multiple **Horizontal Arrangement** on [Designer Viewer](assets//Common//Designer-Viewer.png) ? Absolutely... same as on **Vertical Arrangement**.
    >
    > * **Note [1]** : To make sure the **Horizontal Arrangement** are responsive, make sure you must turn their width property into **Fill parent** or set it into via percent.

---

### Vertical Scroll Arrangement

The **Vertical Scroll Arrangement** and **Vertical Arrangement** is same purpose, to align the user interfaces vertically, except... it can be scrollable, if the child user interface component is occupy and overflow the height of the screen.

* **Step [0]**

    ![Vertical-Scroll-Arrangement-00.png](assets//Chapter-2//Vertical-Scroll-Arrangement-00.png)

    > Go to [Pallete Panel](assets//Common//Pallete-Panel.png) click the **Layout** tab.

    ![Vertical-Scroll-Arrangement-01.png](assets//Chapter-2//Vertical-Scroll-Arrangement-01.png)

    > Drag the **Vertical Scroll Arrangement** and drop it on [Designer Viewer](assets//Common//Designer-Viewer.png).

    ![Vertical-Scroll-Arrangement-02.png](assets//Chapter-2//Vertical-Scroll-Arrangement-02.png)
    ![Vertical-Scroll-Arrangement-03.png](assets//Chapter-2//Vertical-Scroll-Arrangement-03.png)

    > Change the **Vertical Scroll Arrangement** width property from **Automatic** to **Fill Parent**.

* **Step [1]**

    ![Vertical-Scroll-Arrangement-10.png](assets//Chapter-2//Vertical-Scroll-Arrangement-10.png)
    ![Vertical-Scroll-Arrangement-11.png](assets//Chapter-2//Vertical-Scroll-Arrangement-11.png)

    > Go back to [Pallete Panel](assets//Common//Pallete-Panel.png) again and click the **User Interface** tab and drag 11 **Buttons** and put it inside on **Vertical Scroll Arrangement**, and then after that try to run on your **MIT AI2 Companion** and you'll see if it's scrollable or not.
    >
    > #### Take Note :
    > 
    > * **Note [0]** : If your screen height is much larger, it means they are possible cannot be scrollable, but don't worry it's not a bug, although they are not actually overflow by the user interface component.

---

### Horizontal Scroll Arrangement

The **Horizontal Scroll Arrangement** is same as the **Horizontal Arrangement**, although they can scrollable horizontally, when the child user interface component was overflowing the screen width.

* **Step [0]**

    ![Horizontal-Scroll-Arrangement-00.png](assets//Chapter-2//Horizontal-Scroll-Arrangement-00.png)

    > Click the layout tab.

    ![Horizontal-Scroll-Arrangement-01.png](assets//Chapter-2//Horizontal-Scroll-Arrangement-01.png)
    ![Horizontal-Scroll-Arrangement-02.png](assets//Chapter-2//Horizontal-Scroll-Arrangement-02.png)

    > After that... let's drag the **Horizontal Scroll Arrangement** layout and place it under the [Designer Viewer](assets//Common//Designer-Viewer.png)

* **Step [1]**

    ![Horizontal-Scroll-Arrangement-10.png](assets//Chapter-2//Horizontal-Scroll-Arrangement-10.png)

    > Change the **Horizontal Scroll Arrangement** width from **Automatic** to **Fill Parent**.

    ![Horizontal-Scroll-Arrangement-11.png](assets//Chapter-2//Horizontal-Scroll-Arrangement-11.png)

    > Add three buttons and try to test it on your device and see you'll what happen.
    >
    > #### Take Note :
    > 
    > * **Note [0]** : If the child user interface component was overflowing the screen width, then the the scrollability of **Horizontal Scroll Arrangement** will be activated.

---

### Table Arrangement

The **Table Arrangement** is same as **Grid**, though the **Table Arrangement** can make a columns and rows unlike the other layouts, they could be use specifically and much complex to deal with. so if you like to make a **Tic Tac Toe** or **Chess** game, then this is the layout is the best to use of.

* **Step [0]**

    ![Table-Arrangement-00.png](assets//Chapter-2//Table-Arrangement-00.png)
    ![Table-Arrangement-01.png](assets//Chapter-2//Table-Arrangement-01.png)

    > To add a **Table Arrangement** you'll need to click the layout Tab and find the **Table Arrangement** component.

    ![Table-Arrangement-02.png](assets//Chapter-2//Table-Arrangement-02.png)
    ![Table-Arrangement-03.png](assets//Chapter-2//Table-Arrangement-03.png)

    > After you drop the **Table Arrangement** on [Designer Viewer](assets//Common//Designer-Viewer.png), change the columns and rows value to **3** and also change the width of **Table Arrangement** from **Automatic** to **Fill parent**.

* **Step [1]**

    ![Table-Arrangement-10.png](assets//Chapter-2//Table-Arrangement-10.png)
    ![Table-Arrangement-11.png](assets//Chapter-2//Table-Arrangement-11.png)

    > After that you set their property, we need to add a user interface components and By the way i use **button** for this documentation. First i set 9 buttons in it and will see what it looks like.
    >
    > #### Take Note :
    > 
    > * **Note [0]** : There is no spanning property on **Table Arrangement**.
    > * **Note [1]** : You can actually put any user interface components in it.
    > * **Note [2]** : As you can see, i set the columns and rows value to 3, and this would be 3x3.

---

[[Previous](Chapter-1.md)]&nbsp;&nbsp;[[Next](Chapter-3.md)]&nbsp;&nbsp;[[Table of Contents](Index.md#tblcontents)]

###### **Author & Copyright (c)** : Kevin C. Magnifico

###### **License** : MIT Expat license

###### **Initial created** : 2023-12-27

###### **File Format** : Markdown (*.md)
