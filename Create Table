CREATE EXTERNAL TABLE IF NOT EXISTS def ault.credito (
`idade` i n t ,
`sexo` s t r i n g ,
`dependentes` i n t ,
`escolaridade` s t r i n g ,
`estado_civil` s t r i n g ,
`salario_anual` s t r i n g ,
`tipo_cartao` s t r i n g ,
`qtd_produtos` b i g i n t ,
`iteracoes_12m` i n t ,
`meses_inativo_12m` i n t ,
`l i mi te_c redi to` f l o a t ,
`valor_transacoes_12m` f l o a t ,
`qtd_transacoes_12m` i n t
)
ROW FORMAT SERDE 'org.apache.hadoop.hive.serde2.lazy.LazySimpleSerDe'
WITH SERDEPROPERTIES(
' s e r i a l i z a t i o n . f o r m a t ' = ' , ' ,
' f i e l d . d e l i m ' = ' , '
) LOCATION<sua-localizacao>
TBLPROPERTIES ('has_encrypted_data'='false');
