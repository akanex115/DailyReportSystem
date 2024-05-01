# 0. ubuntu:22.04をベースにする
FROM ubuntu:22.04

# 1. DailyReportSystemディレクトリをルートディレクトリに作成して
#    そのなかにfirstvi.txtを作成
RUN mkdir /DailyReportSystem
RUN touch /DailyReportSystem/firstvi.txt

# 2. viのインストール
RUN apt update
RUN apt -y install vim