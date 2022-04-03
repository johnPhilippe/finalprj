<template>
  <div class="section">
    <div class="container">
      <h1>Connect with us</h1>
      <form>

        <input type="email" id="email" name="email" placeholder="Enter your email">

        <input type="text" id="fname" name="firstname" placeholder="Enter your name">

        <input type="text" id="lname" name="lastname" placeholder="Enter your last name">

        <input type="text" id="subject" name="subject" placeholder="subject">

        <textarea id="subject" name="subject" placeholder="Write something" style="height:200px"></textarea>

        <input type="submit" value="Submit">

      </form>
    </div>
  </div>
</template> 
<script>

export default ({
  name:'contact',
  data() {
    return{
      title:'Contact'
    }
  },
})
</script>

<style scoped>
  body{
    font-family: Arial, Helvetica, sans-serif;
  }
  *{
    box-sizing: border-box;
  }
  div h1{
    font-family: "Oswald",sans-serif;
    color: #000;
    text-transform: uppercase;
    text-align: center;
    padding-bottom: 20px;
  }
  .section{
    padding-top: 100px;
    padding-bottom: 100px;
  }

  input[type=text], input[type=email], textarea{
    width: 100%;
    padding: 12px;
    border: 1px solid #ccc;
    box-sizing: border-box;
    margin-top: 6px;
    margin-bottom: 16px;
    resize: vertical;
  }

  input[type=text], input[type=email]{
    border: none;
    border-bottom: 1px solid #ccc;
    outline: none;
  }

  input[type=submit]{
    background-color: #3d3d3d;
    color: white;
    padding: 12px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
  }

  input[type=submit]:hover{
    background-color: #2c3642;
  }

  .section{
    background-color: #e5e8eb;
  }
  .container{
    border-radius: 5px;
    background-color: white;
    padding: 20px;
  }
  
</style>