@Get(): Este decorador marca un método como un controlador para las solicitudes HTTP GET. En este caso, el método postMethod() maneja las solicitudes GET en la ruta especificada ('projectX/test'). Retorna un string que indica el método HTTP utilizado en la solicitud.
![image](https://github.com/CarlosV01/DTO-Nest/assets/125473504/fab5441a-23b5-420d-9805-14fba219ba5b)

@Put(): Este decorador marca un método como un controlador para las solicitudes HTTP PUT. En este caso, el método putMethod() maneja las solicitudes PUT en la ruta especificada ('projectX/test'). Retorna un string que indica que la acción PUT se ha realizado.
![image](https://github.com/CarlosV01/DTO-Nest/assets/125473504/955765a4-d93c-4668-9edd-543488ab024a)

@Post(':id/descripcion/:descripcion/cantidad/:cantidad'): Este decorador marca un método como un controlador para las solicitudes HTTP POST en una ruta específica con parámetros de ruta dinámicos (:yo, :tall, :1.93). En este caso, el método Methodpost() maneja las solicitudes POST en la ruta especificada, y utiliza el decorador @Param() para extraer los parámetros de la solicitud. Retorna un objeto que contiene los parámetros de la solicitud.
![image](https://github.com/CarlosV01/DTO-Nest/assets/125473504/6c6d5e97-fca3-47f4-b9db-bcee9c57f2b3)

@Patch(): Este decorador marca un método como un controlador para las solicitudes HTTP PATCH. En este caso, el método patchMethod() maneja las solicitudes PATCH en la ruta especificada ('projectX/test'). Retorna un string que indica que la acción PATCH se ha realizado.
![image](https://github.com/CarlosV01/DTO-Nest/assets/125473504/007907ee-3ec1-4ee1-8657-9b895ba8c0cf)

@Delete(): Este decorador marca un método como un controlador para las solicitudes HTTP DELETE. En este caso, el método deleteMethod() maneja las solicitudes DELETE en la ruta especificada ('projectX/test'). Retorna un string que indica que la acción DELETE se ha realizado.
![image](https://github.com/CarlosV01/DTO-Nest/assets/125473504/e8eb36fe-d511-4f40-a29a-a386782cc916)
Echo por Carlos Carrasco!
