
<%@page contentType="text/html" pageEncoding="UTF-8"%>
<!DOCTYPE html>
<html>
    <head>
        <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
        <link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/bootswatch/3.3.0/slate/bootstrap.min.css" type="text/css">
      <link href="css/starter-template.css" rel="stylesheet">
      <script>function makeButtonsVisible ()  { 
  $ ( "#discontinueButton" ). 
     removeClass ( "invisible" ); 
  $ ( "#deleteButton" ). removeClass ( "invisible" ); 
}</script>
        <title>PPI.5</title>
    
  </head>

  <body>

    <nav class="navbar navbar-inverse navbar-fixed-top">
      <div class="container">
        <div class="navbar-header">
          <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          <a class="navbar-brand" href="">Projeto Profissional Interdiciprinar</a>
        </div>
        <div id="navbar" class="collapse navbar-collapse">
          <ul class="nav navbar-nav">
            <li>
							<a href="#">Home</a>
						</li>
            <li>
							<a href="#">Sobre</a>
						</li>
            <li><a href="./PPI.5_files/PPI.5.html">Contato</a></li>
          </ul>
        
     
    
          <form class="navbar-form pull-right">
                                    <input type="text" placeholder="Entrada de texto">
                                    <button type="submit" class="btn">
                                        <font><font><font><font>Pesquisar</font></font></font></font>
                                    </button>
                                     <a href="index.jsp"  class=" btn btn-mini btn-danger"  style="
		                               position: relative;
		                               ">Fazer log-out
		                               <i class="icon-off"></i>
		                               </a>
                                    
                                </form>
            
            
        </div><!--/.navbar-collapse -->
        
      </div>
    </nav>

<!-- Main jumbotron for a primary marketing message or call to action -->
    <div class="container-fluid">
	<div class="row">
		<div class="col-md-12">
			<div class="jumbotron">
				<div class="bs-example bs-example-tabs" data-example-id="togglable-tabs">
    <ul id="myTabs" class="nav nav-tabs" role="tablist">
      <li role="presentation" class="active"><a href="#home" id="home-tab" role="tab" data-toggle="tab" aria-controls="home" aria-expanded="true"><font><font>Cadastro de Produto</font></font></a></li>
      <li role="presentation" class=""><a href="#profile" role="tab" id="profile-tab" data-toggle="tab" aria-controls="profile" aria-expanded="false"><font><font>Consulta Estoque</font></font></a></li>
      <li role="presentation" class="dropdown">
        <a href="#" id="myTabDrop1" class="dropdown-toggle" data-toggle="dropdown" aria-controls="myTabDrop1-contents" aria-expanded="false"><font><font>Financeiro </font></font><span class="caret"></span></a>
        <ul class="dropdown-menu" aria-labelledby="myTabDrop1" id="myTabDrop1-contents">
          <li><a href="#dropdown1" role="tab" id="dropdown1-tab" data-toggle="tab" aria-controls="dropdown1"><font><font>Conta a pagar</font></font></a></li>
          <li><a href="#dropdown2" role="tab" id="dropdown2-tab" data-toggle="tab" aria-controls="dropdown2"><font><font>Conta a Receber</font></font></a></li>
        </ul>
      </li>
    </ul>
    <div id="myTabContent" class="tab-content">
      <div role="tabpanel" class="tab-pane fade active in" id="home" aria-labelledby="home-tab">


<div class="container">
	<div class="row">
		
        
        <div class="col-md-12">
        <h4>Tabela de Dados</h4>
        <div class="table-responsive">

                
              <table id="mytable" class="table table-bordred table-striped">
                   
                   <thead>
                   
                   <th><input type="checkbox" id="checkall" /></th>


                   <th>Nome Produto</th>
                    <th>Tipo</th>
                     <th>Codigo</th>
                     <th>Email Fabricante</th>
                     <th>Preço R$</th>
                      <th>Edit</th>
                      
                       <th>Delete</th>
                   </thead>
    <tbody>
    
    <tr>
    <td><input type="checkbox" class="checkthis" /></td>
    <td>CPU</td>
    <td>Un.</td>
    <td>0001</td>
    <td>isometric.mohsin@gmail.com</td>
    <td>7,57</td>
    <td><p data-placement="top" data-toggle="tooltip" title="Edit"><button class="btn btn-primary btn-xs" data-title="Edit" data-toggle="modal" data-target="#edit" ><span class="glyphicon glyphicon-pencil"></span></button></p></td>
    <td><p data-placement="top" data-toggle="tooltip" title="Delete"><button class="btn btn-danger btn-xs" data-title="Delete" data-toggle="modal" data-target="#delete" ><span class="glyphicon glyphicon-trash"></span></button></p></td>
    </tr>
    
 <tr>
    <td><input type="checkbox" class="checkthis" /></td>
    <td>CPU</td>
    <td>Un.</td>
    <td>0001</td>
    <td>isometric.mohsin@gmail.com</td>
    <td>7,57</td>
    <td><p data-placement="top" data-toggle="tooltip" title="Edit"><button class="btn btn-primary btn-xs" data-title="Edit" data-toggle="modal" data-target="#edit" ><span class="glyphicon glyphicon-pencil"></span></button></p></td>
    <td><p data-placement="top" data-toggle="tooltip" title="Delete"><button class="btn btn-danger btn-xs" data-title="Delete" data-toggle="modal" data-target="#delete" ><span class="glyphicon glyphicon-trash"></span></button></p></td>
    </tr>
    
    
 <tr>
    <td><input type="checkbox" class="checkthis" /></td>
    <td>CPU</td>
    <td>Un.</td>
    <td>0001</td>
    <td>isometric.mohsin@gmail.com</td>
    <td>7,57</td>
    <td><p data-placement="top" data-toggle="tooltip" title="Edit"><button class="btn btn-primary btn-xs" data-title="Edit" data-toggle="modal" data-target="#edit" ><span class="glyphicon glyphicon-pencil"></span></button></p></td>
    <td><p data-placement="top" data-toggle="tooltip" title="Delete"><button class="btn btn-danger btn-xs" data-title="Delete" data-toggle="modal" data-target="#delete" ><span class="glyphicon glyphicon-trash"></span></button></p></td>
    </tr>
    
    
    
 <tr>
    <td><input type="checkbox" class="checkthis" /></td>
    <td>CPU</td>
    <td>Un.</td>
    <td>0001</td>
    <td>isometric.mohsin@gmail.com</td>
    <td>7,57</td>
    <td><p data-placement="top" data-toggle="tooltip" title="Edit"><button class="btn btn-primary btn-xs" data-title="Edit" data-toggle="modal" data-target="#edit" ><span class="glyphicon glyphicon-pencil"></span></button></p></td>
    <td><p data-placement="top" data-toggle="tooltip" title="Delete"><button class="btn btn-danger btn-xs" data-title="Delete" data-toggle="modal" data-target="#delete" ><span class="glyphicon glyphicon-trash"></span></button></p></td>
    </tr>
    
    
 <tr>
    <td><input type="checkbox" class="checkthis" /></td>
    <td>CPU</td>
    <td>Un.</td>
    <td>0001</td>
    <td>isometric.mohsin@gmail.com</td>
    <td>7,57</td>
    <td><p data-placement="top" data-toggle="tooltip" title="Edit"><button class="btn btn-primary btn-xs" data-title="Edit" data-toggle="modal" data-target="#edit" ><span class="glyphicon glyphicon-pencil"></span></button></p></td>
    <td><p data-placement="top" data-toggle="tooltip" title="Delete"><button class="btn btn-danger btn-xs" data-title="Delete" data-toggle="modal" data-target="#delete" ><span class="glyphicon glyphicon-trash"></span></button></p></td>
    </tr>
    
   
    
   
    
    </tbody>
        
</table>

<div class="clearfix"></div>
<ul class="pagination pull-right">
  <li class="disabled"><a href="#"><span class="glyphicon glyphicon-chevron-left"></span></a></li>
  <li class="active"><a href="#">1</a></li>
  <li><a href="#">2</a></li>
  <li><a href="#">3</a></li>
  <li><a href="#">4</a></li>
  <li><a href="#">5</a></li>
  <li><a href="#"><span class="glyphicon glyphicon-chevron-right"></span></a></li>
</ul>
                
            </div>
            
        </div>
	</div>
</div>


<div class="modal fade" id="edit" tabindex="-1" role="dialog" aria-labelledby="edit" aria-hidden="true">
      <div class="modal-dialog">
    <div class="modal-content">
          <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-hidden="true"><span class="glyphicon glyphicon-remove" aria-hidden="true"></span></button>
        <h4 class="modal-title custom_align" id="Heading">Edit Your Detail</h4>
      </div>
          <div class="modal-body">
          <div class="form-group">
        <input class="form-control " type="text" placeholder="Mohsin">
        </div>
        <div class="form-group">
        
        <input class="form-control " type="text" placeholder="Irshad">
        </div>
        <div class="form-group">
        <textarea rows="2" class="form-control" placeholder="CB 106/107 Street # 11 Wah Cantt Islamabad Pakistan"></textarea>
    
        
        </div>
      </div>
          <div class="modal-footer ">
        <button type="button" class="btn btn-warning btn-lg" style="width: 100%;"><span class="glyphicon glyphicon-ok-sign"></span> Update</button>
      </div>
        </div>
    <!-- /.modal-content --> 
  </div>
      <!-- /.modal-dialog --> 
    </div>
    
    
    
    <div class="modal fade" id="delete" tabindex="-1" role="dialog" aria-labelledby="edit" aria-hidden="true">
      <div class="modal-dialog">
    <div class="modal-content">
          <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-hidden="true"><span class="glyphicon glyphicon-remove" aria-hidden="true"></span></button>
        <h4 class="modal-title custom_align" id="Heading">Delete this entry</h4>
      </div>
          <div class="modal-body">
       
       <div class="alert alert-danger"><span class="glyphicon glyphicon-warning-sign"></span> Are you sure you want to delete this Record?</div>
       
      </div>
        <div class="modal-footer ">
        <button type="button" class="btn btn-success" ><span class="glyphicon glyphicon-ok-sign"></span> Yes</button>
        <button type="button" class="btn btn-default" data-dismiss="modal"><span class="glyphicon glyphicon-remove"></span> No</button>
      </div>
        </div>
    <!-- /.modal-content --> 
  </div>
      <!-- /.modal-dialog --> 
    </div>
          
          
      </div>
      <div role="tabpanel" class="tab-pane fade" id="profile" aria-labelledby="profile-tab">
        
      <div class="container-fluid">
	<div class="row">
		<div class="col-md-12">
			<table class="table table-striped">
				<thead>
					<tr>
						<th>
							Codigo
						</th>
						<th>
							Product
						</th>
						<th>
							Ultima Entrada
						</th>
						<th>
							Quantidade em Estoque
						</th>
					</tr>
				</thead>
				<tbody>
					<tr class="active">
						<td>
							0001
						</td>
						<td>
							CPU
						</td>
						<td>
							01/04/2012
						</td>
						<td>
							10
						</td>
					</tr>
					<tr class="active">
						<td>
							0001
						</td>
						<td>
							CPU
						</td>
						<td>
							01/04/2012
						</td>
						<td>
							10
						</td>
					</tr>
					<tr class="active">
						<td>
							10
						</td>
						<td>
							CPU
						</td>
						<td>
							01/04/2012
						</td>
						<td>
							10
						</td>
					</tr>
					<tr class="active">
						<td>
							0001
						</td>
						<td>
							CPU
						</td>
						<td>
							01/04/2012
						</td>
						<td>
							10
						</td>
					</tr>
					<tr class="active">
						<td>
							0001
						</td>
						<td>
							CPU
						</td>
						<td>
							01/04/2012
						</td>
						<td>
							10
						</td>
					</tr>
                                        <tr class="active">
						<td>
							0001
						</td>
						<td>
							CPU
						</td>
						<td>
							01/04/2012
						</td>
						<td>
							10
						</td>
					</tr>
                                        
                                        
				</tbody>
			</table>
                    <ul class="pagination pull-right">
  <li class="disabled"><a href="#"><span class="glyphicon glyphicon-chevron-left"></span></a></li>
  <li class="active"><a href="#">1</a></li>
  <li><a href="#">2</a></li>
  <li><a href="#">3</a></li>
  <li><a href="#">4</a></li>
  <li><a href="#">5</a></li>
  <li><a href="#"><span class="glyphicon glyphicon-chevron-right"></span></a></li>
</ul>
		</div>
	</div>
</div>
      </div>
        
        
      <div role="tabpanel" class="tab-pane fade" id="dropdown1" aria-labelledby="dropdown1-tab">
        texto aqui </div>
      <div role="tabpanel" class="tab-pane fade" id="dropdown2" aria-labelledby="dropdown2-tab">
       texto aqui </div>
    </div>
  </div>
                    <div class="container-fluid">
	<div class="row">
		<div class="col-md-12">
			 <a id="modal-222483" href="#modal-container-222483" role="button" class="btn" data-toggle="modal">Novo Lançamento</a>
			
			<div class="modal fade" id="modal-container-222483" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
				<div class="modal-dialog">
					<div class="modal-content">
						<div class="modal-header">
							 
							<button type="button" class="close" data-dismiss="modal" aria-hidden="true">
								×
							</button>
							<h4 class="modal-title" id="myModalLabel">
								Modal title
							</h4>
						</div>
						<div class="modal-body">
							
						</div>
						<div class="modal-footer">
							 
							<button type="button" class="btn btn-default" data-dismiss="modal">
								Close
							</button> 
							<button type="button" class="btn btn-primary">
								Save changes
							</button>
						</div>
					</div>
					
				</div>
				
			</div>
			
		</div>
	</div>
</div>        
                            
			</div>
		</div>
	</div>
</div><!-- /.container -->
 <div class="container">
      <!-- Example row of columns -->
      <div class="row">
        <div class="col-md-4">
      <div class="container-fluid">
	<div class="row">
		<div class="col-md-12">
			<nav class="navbar navbar-default navbar-fixed-bottom" role="navigation">
				
					<ul class="breadcrumb">
				<li>
					<a href="#">Home</a> <span class="divider">/</span>
				</li>
				<li>
					<a href="#">Mapa do Site</a> <span class="divider">/</span>
				</li>
				<li class="active">
					Sair
				</li>
			</ul>
					
					
						</li>
					</ul>
				</div>
				
			</nav>
		</div>
	</div>
</div>
        </div>
      </div>

      <hr>

      <footer>
        <p>&copy; Company 2015</p>
      </footer>
    </div> 
    <!-- /container --> 

    <!-- Bootstrap core JavaScript
    ================================================== -->
    <!-- Placed at the end of the document so the pages load faster -->
    <script src="js/jquery.min.js"></script>
    <script src="js/bootstrap.min.js"></script>
    <script src="js/ie10-viewport-bug-workaround.js"></script>
    <script src="js/ie-emulation-modes-warning.js"></script>


</body><object id="5ba85a1a-8b48-a691-ca0b-7a984bb789b3" width="0" height="0" type="application/gas-events-cef"></object></html>


