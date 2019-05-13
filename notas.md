# Notas del curso

## Enlaces

Enlaces importantes de amazon

1. [SageMaker Python SDK](https://github.com/aws/sagemaker-python-sdk)
2. [Amazon SageMaker Examples](https://github.com/awslabs/amazon-sagemaker-examples)
3. [Documentación de SageMaker](https://sagemaker.readthedocs.io/en/stable/)
4. [Ejemplo propio desde consola](https://github.com/iris9112/amazon_sagemaker_test)
5. [Using Scikit-learn with the SageMaker Python SDK](https://sagemaker.readthedocs.io/en/stable/using_sklearn.html)

## Pasos

1. instalar amazon SageMaker:
 `pip install sagemaker`
2. Instalar [aws CLI](https://docs.aws.amazon.com/es_es/cli/latest/userguide/cli-chap-install.html):
 `pip install awscli``
3. Agregar la ruta del ejecutable al PATH, si lo instalaste como software, si es por medio de pip no es necesario
4. Compruebe que la AWS CLI se ha instalado correctamente:  
 `aws --version`
 `aws-cli/1.16.142 Python/3.6.8 Windows/10 botocore/1.12.132`
5. configurar en la consola el usuario ml que previamente cree en el sitio web:
    ```bash
    aws configure --profile ml_user_predict`
    >> (ml) C:\Users\Isabel>aws configure --profile ml_user_predict
    >> AWS Access Key ID [None]: **tu-id**
    >> AWS Secret Access Key [None]: **tu-clave**
    >> Default region name [None]: us-east-1
    >> Default output format [None]:
    ```
6. Ir a amazon, buscar en servicios a s3 y crear un bucket. Ej: isa-ml-sagemaker
