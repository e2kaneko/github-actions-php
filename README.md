# github-actions-php

[![Actions Status](https://github.com/e2kaneko/github-actions-php/workflows/PHP%20Composer/badge.svg)](https://github.com/e2kaneko/github-actions-php/actions)

## About

GitHub ActionsでPHPのCI/CDを実行するための学習プロジェクトです

## Tools

GitHub Actionsを利用して、以下の処理を実行します

* PHPセットアップ
    * バージョン7.3, 7.4
    * extensions: mbstring, dom, fileinfo, mysql, intl
    * tools: php-cs-fixer, phpunit, phpmd, phpstan, phpcs, phpcpd
* MySQLインストール
    * バージョン5.7
* Laravelインストール
    * composer実行
    * マイグレーション実行
* PHPUnitによる自動テストの実行
* コード計測
    * PHP Mess Detector(PHPMD)
    * PHP_CodeSniffer(PHPCS)
    * PHP Copy/Paste Detector(PHPCPD)
    * PHP Static Analysis Tool(PHPStan)

## License

The scripts and documentation in this project are released under the [MIT License](LICENSE)

