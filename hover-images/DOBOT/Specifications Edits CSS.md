/* Specifications Section Original CSS */

.spec-table-wrap {display:flex; justify-content: center;}
.spec-table-header { font-weight: 600; padding-bottom: 10px; margin-bottom:30px; text-transform: uppercase; text-decoration:underline;}
.spec-table-info-wrap {display:flex;}
.spec-table-info-wrap ul { list-style-type: none; padding-left:20px !important;}
.spec-table-info-wrap li { padding-bottom: 10px;}
.spec-table-info-title {font-weight: 600;  text-transform: uppercase; }
.spec-table-info-title
.spec-table-info-data {}
.spec-table-box { flex: 0 1 500px;
  margin: 5px; padding: 5px;}

.spec-wrap { }
.spec-inner { display:flex; justify-content: center; }

.spec-table {min-width: 40%; padding: 20px; margin-right: 20%; }
.spec-table ul {list-style-type:none; padding-left: 20px; }
.spec-table ul li {padding-bottom:10px;  }

.spec-table-inner { display:flex; }

.spec-table-title { font-weight: 600; padding-bottom: 10px; text-transform: uppercase; min-width: 50%; }
.spec-table-title ul { list-style-type:none; }
.spec-table-title ul > li:only-child {
  display: none;
}

.spec-table-data {}
.spec-table-data > li:only-child {
  display: none;
}







/* Specifications Section this is what i changed in the fist place */

/*This will fix the word specifications*/
h2.product-details-title.container {
  margin-left: 185px;
  max-width: 380px;
}

div.spec-table-wrap {

}

/*This will fix the word specifications mobile version*/
@media (max-width: 736px){
  h2.product-details-title.container {
    margin-left: 28px;
    max-width: 380px;
  }
}

/*This will fix the word specifications tablet version*/
@media (max-width: 1024px){
  h2.product-details-title.container {
    margin-left: 14px;
    max-width: 380px;
  }
}



/*MESS AROUND WITH THIS CODE*/
/*This effects the float elements*/
.spec-table-wrap {
  display:flex; 
 justify-content: center;
}

/*This will affect all tables INDEPENDENTLY*/
.spec-table-box { 
  flex: 0 1 500px;
  margin-right: 97px;
  padding: 5px;
}

div.spec-hide-table1 {
    width: 680px;
}

div.spec-hide-table2 {
    width: 680px;
}

div.spec-hide-table3 {
    width: 680px;
}

div.spec-hide-table4 {
    width: 680px;
}


/* Specifications Section Jesus Edits*/

/*This will fix the word specifications*/
h2.product-details-title.container {
  margin-left: 20px;
  max-width: 860px;
  padding: 0px;
  text-align: center;
}

/*This will fix the word specifications mobile version*/
@media (max-width: 736px){
  h2.product-details-title.container {
    margin-left: 14px;
    max-width: 380px;
    text-align: left;
  }
}

/*This will fix the word specifications tablet version*/
/*I will have to worry about this at a later time (desktop & mobile first!*/
@media (max-width: 1024px){
  h2.product-details-title.container {
    margin-left: 28px;
    max-width: 380px;
    text-align: left;
  }
}

/*Effects the wrap on where the content should start EDIT HERE*/
div.spec-table-wrap {
  display:flex; 
  justify-content: center;
  flex-wrap: wrap;
  align-items: left;
}

/*MESS AROUND WITH THIS CODE*/
/*This effects the float elements*/
.spec-table-wrap {
  display:flex; 
  justify-content: center;
  flex-wrap: wrap;
  align-items: left;
}

/*This will affect ALL tables INDEPENDENTLY*/
.spec-table-box { 
  flex: 0 1 500px;
  margin: 5px;
  padding: 5px;
}

/*I added this for testing*/
/*This effects the size of each spec independently! Boxes: 1-4*/
div.spec-hide-table1 {
  width: 680px;
}

div.spec-hide-table2 {
  width: 680px;
}

div.spec-hide-table3 {
  width: 680px;
}

div.spec-hide-table4 {
  width: 680px;
}

ul.spec-table-info-data {
padding-left: 0px;
}

/*Effects the wrap on where the content should start EDIT HERE*/
div.spec-table-wrap {
  display: flex; 
  justify-content: center;
  flex-wrap: wrap;
}

/*THESE NEXT TO LINES OF CODE MAKES IT WORK*/
/*Effects the wrap on where the content should start (should be centered) EDIT HERE*/
div.spec-table-wrap {
  display: flex; 
  justify-content: center;
  flex-wrap: wrap;
  margin-left: 0px;
  margin-right: 0px;
}
/*This will fix the word specifications mobile version*/
@media (max-width: 667px){
  div.spec-table-wrap {
    display: flex; 
    justify-content: left;
    flex-wrap: wrap;
    margin-left: 0px;
    margin-right: 0px;
  }
}



/* Specifications Section Jesus Edits*/

/*This will fix the word specifications CHECK*/
h2.product-details-title.container {
  padding-left: 10px;
}

/*This will fix the word specifications mobile version CHECK*/
@media (max-width: 667px){
  h2.product-details-title.container {
    margin-left: 14px;
    max-width: 380px;
    text-align: left;
  }
}

/*This will fix the word specifications tablet version HOLD*/
/*I will have to worry about this at a later time (desktop & mobile first!*/
@media (max-width: 1024px){
  h2.product-details-title.container {
    margin-left: 28px;
    max-width: 380px;
    text-align: left;
  }
}

/*This will fix the word specifications mobile version CHECK*/
@media (max-width: 667px){
  div.spec-table-wrap {
    display: flex; 
    justify-content: left;
    flex-wrap: wrap;
    margin-left: 0px;
    margin-right: 0px;
  }
}

/*Effects the wrap on where the content should start (should be centered) CHECK*/
div.spec-table-wrap {
  display: flex; 
  justify-content: center;
  flex-wrap: wrap;
  margin-left: 0px;
  margin-right: 0px;
}

/*MESS AROUND WITH THIS CODE*/
/*This effects the float elements*/
.spec-table-wrap {
  display:flex; 
  justify-content: left;
  flex-wrap: wrap;
}

/*This will affect ALL tables INDEPENDENTLY*/
.spec-table-box { 
  flex: 0 1 720px;
  margin: 5px;
  padding: 5px;
}

/*I added this for testing*/
/*This effects the size of each spec independently! Boxes: 1-4*/
div.spec-hide-table1 {
  width: 720px;
}

div.spec-hide-table2 {
  width: 720px;
}

div.spec-hide-table3 {
  width: 720px;
}

div.spec-hide-table4 {
  width: 720px;
}

.spec-table-header { font-weight: 600; padding-bottom: 10px; padding-left: 20px; margin-bottom:30px; text-transform: uppercase; text-decoration:underline;}
.spec-table-info-wrap {display:flex;}
.spec-table-info-wrap ul { list-style-type: none; padding-left:20px !important;}
.spec-table-info-wrap li { padding-bottom: 10px;}
.spec-table-info-title {font-weight: 600;  text-transform: uppercase; }
.spec-table-info-title
.spec-table-info-data {}

.spec-wrap { }
.spec-inner { display:flex; justify-content: center; }

.spec-table {min-width: 40%; padding: 20px; margin-right: 20%; }
.spec-table ul {list-style-type:none; padding-left: 20px; }
.spec-table ul li {padding-bottom:10px;   }

.spec-table-inner { display:flex; }



.spec-table-title { font-weight: 600; padding-bottom: 10px; text-transform: uppercase; min-width: 50%; }
.spec-table-title ul { list-style-type:none; }
.spec-table-title ul > li:only-child {
  display: none;
}

.spec-table-data {}
.spec-table-data > li:only-child {
  display: none;
}


