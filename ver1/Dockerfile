# 0. ubuntu:22.04をベースにする
FROM ubuntu:22.04

# 1. ディレクトリをルートディレクトリに作成して
#    そのなかにfirstvi.txtを作成
RUN mkdir /daily_report_system
RUN touch /daily_report_system/firstvi.txt

# 2. viのインストール
RUN apt update
RUN apt -y install vim