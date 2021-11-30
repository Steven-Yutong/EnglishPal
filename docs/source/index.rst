.. EnglishPal documentation master file, created by
   sphinx-quickstart on Sat Nov 27 20:15:28 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to EnglishPal's documentation!
======================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:
   

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`


Lab1：Dependency Analysis and Dependency Graph
==============================================

小组成员信息： 201932110143 王炫 201932110145 邬程峰 201932110146 吴彬宇
201932110147 吴雨桐 201932110148 谢铭轩

项目Gitee地址：\ `Gitee <https://gitee.com/dearxuan/EnglishPal.git>`__

项目Read the Docs地址：\ `Read the Docs <https://www.baidu.com>`__

Abstract
--------

借助工具研究EnglishPal现有的模块(或类)之间的依赖关系，了解EnglishPal的架构目前的健康水平，并对当前的架构进行优缺点分析。

Introduction
------------

EnglishPal是一款面向希望提升自身英语阅读能力的用户，提供英语文章学习服务的轻量级在线网站。
   
它内设了多达百篇不同难度等级的文章，会根据用户的英语水平为用户提供相应难度的文章进行练习；
   
同时，每一个用户还享有独立的生词本，用户可以将在阅读文章过程中遇到的生词收集起来，在复习中进行针对性记忆。
   
本次实验的目的是通过模块和类及函数两个层面对该项目进行依赖分析，判断模块间、类间的耦合程度以及整体架构的健康水平，为之后的系统维护作准备。
