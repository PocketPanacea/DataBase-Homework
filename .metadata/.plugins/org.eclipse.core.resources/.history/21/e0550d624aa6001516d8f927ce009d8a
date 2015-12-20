<%@ page language="java" contentType="text/html; charset=ISO-8859-1"
    pageEncoding="ISO-8859-1"%>
    
<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<html>
<head>
	
	<meta http-equiv="Content-Type" content="text/html; charset=ISO-8859-1">
	<title>Test Page</title>
	
	<% String static_path = request.getContextPath(); %>
		
	<link rel="stylesheet" type="text/css" href="<%= static_path %>/Csses/semantic.min.css">
    <script src="<%= static_path %>/Javascripts/jquery.min.js"></script>
    <script src="<%= static_path %>/Javascripts/semantic.min.js"></script>
	
</head>

<body>
	<style type="text/css">
   body {
     background-color: #DADADA;
   }
   #main {
     width: 450px;
   }
   #page {
     margin-top: 20px;
   }
  </style>
  <div id ="page" class="ui middle aligned center aligned grid">
    <div id="main" class="cloumn">
      <h2 class="ui header">
        <i class="ui users icon"></i>
        <div class="content">
          Login
          <div class="sub header">XueOnline</div>
        </div>
      </h2>
      <div class="ui stacked segment">
        <div class="field">
          <div class="ui left icon input">
            <i class="user icon"></i>
            <input name="username" placeholder="your user name" type="text">
          </div>
        </div>
        <div class="field">
          <div class="ui left icon input">
            <i class="lock icon"></i>
            <input name="password" placeholder="your password" type="password">
          </div>
        </div>
        <button class="ui fluid blue submit button" type="submit">Login</button>
      </div>
      <div class="ui error message">
        <p>{{ errormsg }}</p>
      </div>
          </form>
          <div class="ui icon message">
            <i class="add user icon"></i>
            <div class="content">
            </div>
          </div>
    </div>
  </div>
</body>

</html>