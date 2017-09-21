node {
	stage 'Checkout'
		checkout scm

	stage 'Build'
		sh 'dotnet build -r Release hwapp.csproj'

	stage 'Archive'
		archive 'hwapp.csproj/bin/Release/**'

}

