# Reactjs
My first respository on github
Implement for hooks
--------------------
      App.js
--------------------
import React,{useState} from 'react'
//import Header from './Header'

function App(){
	var style={
		background:"green"
	}
	var changeBackground=(e)=>{
		e.target.style.background="green";
	}
	var changeBackground=(e)=>{
	e.target.setAttribute('class','changeBackground')
	}
	const [data,setData]=useState({"name":"Likhitha","role":"Software Engenieer"})
	return (
		<>
			<h2 onMouseOver={(e)=>{changeBackground(e)}}> {data.name} is working as {data.role}. </h2>
		</>
	)
}



import React,{useState} from 'react'
import './App.css';
import Header from './Header';
function App(){
  return(
    <>
      <h2> Sample Data </h2>
      <Header name="Likhitha" role="Fresher" />
    </>
  )
}
export default App;



     Header.js
let Header=(props)=>{
  return {
    

















