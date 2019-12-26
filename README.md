# Cidades Grátis
[![Latest Stable Version](https://poser.pugx.org/composer require gleisonnanet/cidades-gratis/cidades-gratis/v/stable.svg)](https://packagist.org/packages/composer require gleisonnanet/cidades-gratis/cidades-gratis) 
[![Total Downloads](https://poser.pugx.org/composer require gleisonnanet/cidades-gratis/cidades-gratis/downloads.svg)](https://packagist.org/packages/composer require gleisonnanet/cidades-gratis/cidades-gratis) 
[![Latest Unstable Version](https://poser.pugx.org/composer require gleisonnanet/cidades-gratis/cidades-gratis/v/unstable.svg)](https://packagist.org/packages/composer require gleisonnanet/cidades-gratis/cidades-gratis)
[![MIT license](https://poser.pugx.org/composer require gleisonnanet/cidades-gratis/nfephp-serialize/license.svg)](http://opensource.org/licenses/MIT)

Com esse pacote você poderá consultar, gratuitamente, Cidades diretamente no site do IBGE.

### Como utilizar

Adicione a library

```sh
$ composer require composer require gleisonnanet/cidades-gratis/cidades-gratis
```

Adicione o autoload.php do composer no seu arquivo PHP.

```php
require_once 'vendor/autoload.php';  
```

### Métodos

##### Buscar UFs

Use o método `getUfs()` para retornar a lista de UFs com seus respecivos códigos

```php
$ufs = composer require gleisonnanet/cidades-gratis\CidadesGratis\Cidades::getUfs();
```

##### Buscar Cidades

Use o método `getCidades()` para retornar a lista de Cidades com seus respecivos códigos de uma determinada UF

```php
$cidades = composer require gleisonnanet/cidades-gratis\CidadesGratis\Cidades::getCidades(31);
```

##### Buscar detalhes de uma cidade

Use o método `getCidadeDetalhes()` para retornar a detalhes de uma determinada cidade

```php
$detalhes = composer require gleisonnanet/cidades-gratis\CidadesGratis\Cidades::getCidadeDetalhes(310620);
```

### Builds

Dentro da pasta `build/` existe dois arquivos: `ufs.json` e `cidades.json`. Eles foram gerados no dia 20/08/2015

### Gostou? Conheça também

* [CnpjGratis](https://github.com/composer require gleisonnanet/cidades-gratis/cnpj-gratis)
* [CpfGratis](https://github.com/composer require gleisonnanet/cidades-gratis/cpf-gratis)
* [CepGratis](https://github.com/composer require gleisonnanet/cidades-gratis/cep-gratis)
* [NFePHPSerialize](https://github.com/composer require gleisonnanet/cidades-gratis/nfephp-serialize)

### License

The MIT License (MIT)
