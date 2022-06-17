<script>
	import { Router, Link, Route } from "svelte-routing";
	import Home from "./routes/Home.svelte";
	import Login from "./routes/Login.svelte";
</script>

<div>
	<h1>Hola ddMunddsdso</h1>
	<Router>
		<nav>
			<Link to = "/" >HOME</Link>
			<Link to = "/Login" >login</Link>
		</nav>

		<Route path ="/">
			<Home></Home>
		</Route>
		<Route path ="/Login">
			<Login></Login>
		</Route>
	</Router>
</div>