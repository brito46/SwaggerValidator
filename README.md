# SwaggerValidator

This project shows a "valid swagger" badge on my webpage, supporting Swagger/OpenAPI 2.0 and OpenAPI 3.0 specifications.
There is an online version hosted on http://validator.swagger.io.

I hosted my webpage using github pages because local and non http/https urls are rejected by default.

I validated my OpenAPI/Swagger specification against the Swagger/OpenAPI 2.0 Schema and OpenAPI 3.0 Schema as follows:
'''HTML
<img src="http://validator.swagger.io/validator?url={Your_URL_Goes_Here}"> 
'''
