node {
	stage 'Checkout'
		checkout scm

	stage 'Build'
		sh 'dotnet build hwapp.csproj'

	stage 'Archive'
		archive 'hwapp.csproj/bin/Release/**'

}

