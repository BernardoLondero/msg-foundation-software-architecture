# MSG Foundation - Arquitetura de Software (UML)

Este repositório contém a modelagem arquitetural de alto nível para o sistema de concessão de hipotecas da MSG Foundation, desenvolvida através de um Diagrama de Componentes UML.

## Objetivo do Projeto
O objetivo foi projetar a estrutura modular do sistema, definindo os componentes internos, suas responsabilidades, e os contratos de comunicação (interfaces) necessários para o funcionamento e integração com serviços externos.

## Escopo da Arquitetura
O diagrama mapeia a separação de responsabilidades do sistema nos seguintes módulos estruturais:
* Core Business: Componentes de `Gestão de Hipotecas`, `Gestão Financeira` e `Gerador de Relatórios`, expondo interfaces de controle e cálculo de fundos.
* Integração Externa: O componente `Adaptador Bancário`, responsável por intermediar a comunicação segura com o `Sistema Bancário Externo` via API.
* Persistência: O componente de `Persistência de Dados`, que centraliza as interfaces de busca e salvamento, abstraindo o acesso ao Banco de Dados.

## Arquivos do Projeto
* diagrama-componentes-msg-foundation.png: Visualização gráfica do Diagrama de Componentes UML.
