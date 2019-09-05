# 某电商数据分析
## 1.1 数据集简介
以下是从Kaggle上获取到的英国某在线零售业务的用户消费数据,链接地址是：[https://www.kaggle.com/carrie1/ecommerce-data/]  
该数据集为英国在线零售商在2010年12月1日至2011年12月9日间发生的所有网络交易订单信息，包括客户编号、订单编号、商品代码及数量、单价等字段。该公司主要销售礼品，拥有许多批发商客户。  
## 1.2 数据集内容  
数据集为xlsx格式，文件大小22.6M。数据共计8个字段，541908条。具体字段如下：  
1、InvoiceNo：发票编号。为每笔订单唯一分配的6位整数。若以字母'C'开头，则表示该订单被取消。  
2、StockCode：产品代码。为每个产品唯一分配的编码。  
3、Description：产品描述。  
4、Quantity：数量。每笔订单中各产品分别的数量。  
5、InvoiceDate：发票日期和时间。每笔订单发生的日期和时间。  
6、UnitPrice：单价。单位产品价格，单位为英镑。  
7、CustomerID：客户编号。为每个客户唯一分配的5位整数。  
8、Country：国家。客户所在国家/地区的名称。  
## 1.3 提出问题和分析思路 
我们一般围绕人货场三个维度无分析，此数据集并没有包含太多信息，我们从场，人两个维度去分析
1.场：消费趋势分析
按照月作为单位，从以下的四个维度进行国内分析  
* 购买人数  
* 订单数  
* 销量  
* 销售额  
2.人：  
* 复购率  
* 用户分层  
* 用户生命周期、留存率  
* RFM模型构建 
具体分析见html文件
