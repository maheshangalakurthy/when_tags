node{
	stage('Build'){
	if(env.TAG_NAME!==null){
		println("We are building a tag & tag ${env.TAG_NAME}")
	}
	else{
		println("We are building a branch")
	}

	if(env.TAG_NAME=="release:1.0"){
		println("We are Building Sepcifically release:1.0")
	}

	else{
		println("No Tag is found")
	}
	}
}
