<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
    <title>Form with Bootstrap</title>

    <!-- Bootstrap -->
    <link href="css/bootstrap.min.css" rel="stylesheet">

    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.3/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->
  </head>
  <body>
    <div class="container">
      <div class="row">
        <div class="col-lg-6">
          <h2>U. S. Standard Certificate of Live Birth </h2>
        </div>
      </div>
    </div>
    
    
    <div class="container well">
    <form action="">
      <!-- THis is left side -->
        <div class="row">
          <div class="col-md-4">
          <h3>Child's Details</h3>
            <div class="row">
              <div class="col-md-6">
                <div class="form-group">
                  <label for="firstName">First Name</label>
                  <input type="text" class="form-control" id="firstName" placeholder="">
                </div>
              </div>

              <div class="col-md-6">
                <div class="form-group">
                  <label for="middleName">Middle Name</label>
                  <input type="text" class="form-control" id="middleName" placeholder="">
                </div>
              </div>
            </div>

            <div class="row">
              <div class="col-md-6">
                <div class="form-group">
                  <label for="lastName">Last Name</label>
                  <input type="text" class="form-control" id="lastName" placeholder="">
                </div>
              </div>

              <div class="col-md-6">
                <div class="form-group">
                  <label for="suffix">Suffix</label>
                  <input type="text" class="form-control" id="firstName" placeholder="">
                </div>
              </div>
            </div>

            <div class="row">
              <div class="col-md-12">
                <div class="form-group">
                  <label for="lastName">Time of Birth</label>
                  <input type="text" class="form-control" id="lastName" placeholder="">
                </div>
              </div>
            </div>

            <div class="row">
              <div class="col-md-6">
                <div class="form-group">
                  <label for="sex">Sex</label>
                  <select class="form-control">
                    <option>Male</option>
                    <option>Female</option>
                  </select>
                </div>
              </div>

              <div class="col-md-6">
                <div class="form-group">
                  <label for="middleName">Date of Birth</label>
                  <input type="text" class="form-control" id="middleName" placeholder="">
                </div>
              </div>
            </div>
            <div class="row">
              <div class="col-md-12">
                <div class="form-group">
                  <label for="lastName">Facility</label>
                  <input type="text" class="form-control" id="lastName" placeholder="">
                </div>
              </div>
            </div>
            <div class="row">
              <div class="col-md-12">
                <div class="form-group">
                  <label for="lastName">City, Town or location</label>
                  <input type="text" class="form-control" id="lastName" placeholder="">
                </div>
              </div>
            </div>
            <div class="row">
              <div class="col-md-12">
                <div class="form-group">
                  <label for="lastName">Country of Birth</label>
                  <input type="text" class="form-control" id="lastName" placeholder="">
                </div>
              </div>
            </div>

            <h3>Father's Details</h3>
            <p class="help-block">FATHER'S CURRENT LEGAL, NAME</p>
            <div class="row">
              <div class="col-md-6">
                <div class="form-group">
                  <label for="firstName">First Name</label>
                  <input type="text" class="form-control" id="firstName" placeholder="">
                </div>
              </div>

              <div class="col-md-6">
                <div class="form-group">
                  <label for="middleName">Middle Name</label>
                  <input type="text" class="form-control" id="middleName" placeholder="">
                </div>
              </div>
            </div>

            <div class="row">
              <div class="col-md-6">
                <div class="form-group">
                  <label for="lastName">Last Name</label>
                  <input type="text" class="form-control" id="lastName" placeholder="">
                </div>
              </div>

              <div class="col-md-6">
                <div class="form-group">
                  <label for="suffix">Suffix</label>
                  <input type="text" class="form-control" id="firstName" placeholder="">
                </div>
              </div>
            </div>
            <div class="row">
              <div class="col-md-12">
                <div class="form-group">
                  <label for="lastName">Date of Birth</label>
                  <input type="text" class="form-control" id="lastName" placeholder="">
                </div>
              </div>
            </div>
            <div class="row">
              <div class="col-md-12">
                <div class="form-group">
                  <label for="lastName">Birth Place</label>
                  <input type="text" class="form-control" id="lastName" placeholder="">
                </div>
              </div>
            </div>
            <h3>Certifier's Details</h3>
            <div class="row">
              <div class="col-md-12">
                <div class="form-group">
                  <label for="cName">Certifier's Name</label>
                  <input type="text" class="form-control" id="cName" placeholder="">
                </div>
              </div>
            </div>
            <div class="row">
              <div class="col-md-12">
                <div class="form-group">
                  <label for="title">Title</label><br>
                  <label class="checkbox-inline">
                    <input type="checkbox" id="inlineCheckbox1" value="option1"> MD
                  </label>
                  <label class="checkbox-inline">
                    <input type="checkbox" id="inlineCheckbox2" value="option2"> DO
                  </label>
                  <label class="checkbox-inline">
                    <input type="checkbox" id="inlineCheckbox3" value="option3"> HOSPITAL ADMIN
                  </label>
                  <label class="checkbox-inline">
                    <input type="checkbox" id="inlineCheckbox4" value="option1"> CNN/CM
                  </label>
                  <label class="checkbox-inline">
                    <input type="checkbox" id="inlineCheckbox5" value="option2"> OTHER MIDWIFE
                  </label>
                  <label class="checkbox-inline">
                    <input type="checkbox" id="inlineCheckbox6" value="option3"> OTHER (Specify)
                  </label>
                  <input type="text" class="form-control" id="lastName" placeholder="">
                </div>
              </div>
            </div>
            <div class="row">
              <div class="col-md-6">
                <div class="form-group">
                  <label for="lastName">Date Certified</label>
                  <input type="text" class="form-control" id="lastName" placeholder="">
                </div>
              </div>

              <div class="col-md-6">
                <div class="form-group">
                  <label for="suffix">Date Field by Register</label>
                  <input type="text" class="form-control" id="firstName" placeholder="">
                </div>
              </div>
            </div>
            <div class="row">
              <div class="col-md-12">
                <div class="form-group">
                  <label for="lastName">Telephone</label>
                  <input type="text" class="form-control" id="lastName" placeholder="">
                </div>
              </div>
            </div>
            <div class="row">
              <div class="col-md-12">
                <div class="form-group">
                  <label for="lastName">UR#</label>
                  <input type="text" class="form-control" id="lastName" placeholder="">
                </div>
              </div>
            </div>
            
            <div class="row">
              <div class="col-md-12">
                <div class="form-group">
                  <label for="cName">Referring Hospital</label>
                  <input type="text" class="form-control" id="cName" placeholder="">
                </div>
              </div>
            </div>

          </div>

          <!-- THis is right side -->
          <div class="col-md-4 col-md-offset-4">
            <h3>Mother's Details</h3>
            <p class="help-block">MOTHER'S CURRENT LEGAL NAME</p>
            <div class="row">
              <div class="col-md-6">
                <div class="form-group">
                  <label for="firstName">First Name</label>
                  <input type="text" class="form-control" id="firstName" placeholder="">
                </div>
              </div>

              <div class="col-md-6">
                <div class="form-group">
                  <label for="middleName">Middle Name</label>
                  <input type="text" class="form-control" id="middleName" placeholder="">
                </div>
              </div>
            </div>

            <div class="row">
              <div class="col-md-6">
                <div class="form-group">
                  <label for="lastName">Last Name</label>
                  <input type="text" class="form-control" id="lastName" placeholder="">
                </div>
              </div>

              <div class="col-md-6">
                <div class="form-group">
                  <label for="suffix">Suffix</label>
                  <input type="text" class="form-control" id="firstName" placeholder="">
                </div>
              </div>
            </div>

            <div class="row">
              <div class="col-md-12">
                <div class="form-group">
                  <label for="lastName">Date of Birth</label>
                  <input type="text" class="form-control" id="lastName" placeholder="">
                </div>
              </div>
            </div>
            
            <p class="help-block">Mother's name prior to first marriage</p>
            <div class="row">
              <div class="col-md-6">
                <div class="form-group">
                  <label for="firstName">First Name</label>
                  <input type="text" class="form-control" id="firstName" placeholder="">
                </div>
              </div>

              <div class="col-md-6">
                <div class="form-group">
                  <label for="middleName">Middle Name</label>
                  <input type="text" class="form-control" id="middleName" placeholder="">
                </div>
              </div>
            </div>

            <div class="row">
              <div class="col-md-6">
                <div class="form-group">
                  <label for="lastName">Last Name</label>
                  <input type="text" class="form-control" id="lastName" placeholder="">
                </div>
              </div>

              <div class="col-md-6">
                <div class="form-group">
                  <label for="suffix">Suffix</label>
                  <input type="text" class="form-control" id="firstName" placeholder="">
                </div>
              </div>
            </div>

            <div class="row">
              <div class="col-md-12">
                <div class="form-group">
                  <label for="lastName">Birth place</label>
                  <input type="text" class="form-control" id="lastName" placeholder="">
                </div>
              </div>
            </div>
            <div class="row">
              <div class="col-md-12">
                <div class="form-group">
                  <label for="lastName">Residence of Mother State</label>
                  <input type="text" class="form-control" id="lastName" placeholder="">
                </div>
              </div>
            </div>
            <div class="row">
              <div class="col-md-12">
                <div class="form-group">
                  <label for="lastName">Country</label>
                  <input type="text" class="form-control" id="lastName" placeholder="">
                </div>
              </div>
            </div>
            
            <div class="row">
              <div class="col-md-12">
                <div class="form-group">
                  <label for="cName">City, Town or Location</label>
                  <input type="text" class="form-control" id="cName" placeholder="">
                </div>
              </div>
            </div>
            <div class="row">
              <div class="col-md-12">
                <div class="form-group">
                  <label for="lastName">Street and Number</label>
                  <input type="text" class="form-control" id="lastName" placeholder="">
                </div>
              </div>
            </div>
            <div class="row">
              <div class="col-md-12">
                <div class="form-group">
                  <label for="lastName">Appartment No.</label>
                  <input type="text" class="form-control" id="lastName" placeholder="">
                </div>
              </div>
            </div>
            
            <div class="row">
              <div class="col-md-6">
                <div class="form-group">
                  <label for="cName">Zip code</label>
                  <input type="text" class="form-control" id="cName" placeholder="">
                </div>
              </div>
              <div class="col-md-6">
                <div class="form-group">
                  <label for="cName">Inside city Limits</label><br>
                  <label class="radio-inline">
                    <input type="radio" name="inlineRadioOptions" id="inlineRadio1" value="option1"> Yes
                  </label>
                  <label class="radio-inline">
                    <input type="radio" name="inlineRadioOptions" id="inlineRadio2" value="option2"> No
                  </label>
                </div>
              </div>
              
            </div>
            

          </div>
          </div>


        </div>
    </form>
    </div>

    <script src="js/jquery.min.js"></script>
    <!-- Include all compiled plugins (below), or include individual files as needed -->
    <script src="js/bootstrap.min.js"></script>
  </body>
</html>

![form-with-boot](https://user-images.githubusercontent.com/24538019/35844499-189bb014-0b38-11e8-829c-479945b86007.PNG)
