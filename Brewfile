#!/bin/bash

# 参考URL
# http://engineer.wantedly.com/2014/02/25/elasticsearch-at-wantedly-1.html

brew install elasticsearch
brew install mecab

# marvel plugin（コンソール）
/usr/local/bin/plugin -install elasticsearch/marvel/latest

# inquisitor （analyzerを試すのに便利らしい）
/usr/local/bin/plugin -install polyfractal/elasticsearch-inquisitor
# http://localhost:9200/_plugin/inquisitor/#/

# kuromoji (形態素解析エンジン）
/usr/local/bin/plugin -install elasticsearch/elasticsearch-analysis-kuromoji/2.0.0.RC1
