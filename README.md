# site-oficial-DRF

Nota: Os campos relacionais são declarados em relations.py, mas por convenção você deve importá-los do serializersmódulo, usando from rest_framework import serializerse se referir aos campos como serializers.<FieldName>.

many- Se aplicado a um relacionamento de muitos para muitos, você deve definir este argumento como True.

Argumentos :
queryset- O conjunto de consultas usado para pesquisas de instâncias do modelo ao validar a entrada do campo. Os relacionamentos devem definir um conjunto de consultas explicitamente ou definir read_only=True.

many- Se aplicado a um relacionamento de muitos para muitos, você deve definir este argumento como True.

allow_null- Se definido como True, o campo aceitará valores de Noneou a string vazia para relacionamentos anuláveis. O padrão é False.

pk_field- Defina um campo para controlar a serialização/desserialização do valor da chave primária. Por exemplo, pk_field=UUIDField(format='hex')serializaria uma chave primária UUID em sua representação hexadecimal compacta.
