	设备运维管理系统方案V1.1
<br />	文件编写：王磊
<br />	
<br />	1、项目内容：在设备管理系统上进行数据维护、维修管理、备品备件管理、维修管理、绩效管理、项目设备管理。将“人机料法环”整合在系统中，有效提高管理运维效率。
<br />	2、系统基础信息
<br />	(1)角色管理：名称、权限、状态。
<br />	(2)账号信息管理：姓名、部门、员工编号、登陆名、密码、最后登陆时间、是否域用户、域用户名。
<br />	(3)账号密码安全策略：密码长度、历史保存几次、密码有效时间、长期不使用天数锁定。
<br />	(4)职员信息管理：姓名、部门、员工编号、电话，第三方系统比对姓名、员工编号。
<br />	3、备品备件管理 
<br />	(1)备品备件的基础信息维护：备品名称、规格、库位、单位（个/箱/KG....)、最小库存量。
<br />	(2)备品备件的入库：分批次、供应商、供应事件、采购单号、入库时间、入库操作员，单价。
<br />	(3)备品备件的出库：领用人、设备运维单号、领用时间、仓库管理员、批次、数量。审批附件、状态。
<br />	(4)备品备件退库：领用人、出库单号、仓库管理员、数量、退库时间。
<br />	(5)备品备件报废：仓库管理员、批次、数量、说明。
<br />	(6)备品备件报废退库：仓库管理员、批次、数量、说明。
<br />	(7)入库报表、出库报表、报废报表。
<br />	(8)报废件选项：价格、使用时间。
<br />	(9)盘点功能：盘点人、盘点时间、数据明细、备件库存变更记录。（盘点中有备件零件号、数量、批次），附件。
<br />	(10)盘点库存调整：选择当前一个或多个盘点数据进行确认，并选择或者确认一个盘点数据，进行库存调整。
<br />	(11)盘点调整记录。
<br />	4、设备资产管理
<br />	(1)设备基础信息：设备型号、工装编号、电压、供应商、制造日期、总功率、气压、重量、外形尺寸长宽高（L W H）
<br />	(2)工厂布局图：  CAD平面图纸。
<br />	(3)设备信息：设备工位标识。（二维码打印）
<br />	(4)设备记录：使用部门、责任人、时间、状态（入场、项目）。
<br />	(5)设备报废：报废人、审批编号、时间、审批附件。
<br />	(6)设备报表，按时间、项目筛选。
<br />	5、运维管理
<br />	(1)维修管理： 
<br />	①生产部门职员扫面二维码、问题描述、是否停线、影响工位数量、指派部门/电脑选择设备提报问题。
<br />	②维修人员：维修前，查看问题列表、设备历史维护/维修记录、设备相关文件、确认接受任务。维修中：领取备件、查看文件、历史记录等。维修后，维修完成，填写问题原因、处理方式、环境信息（气温、适度）。
<br />	(2)计划维护管理：
<br />	①计划任务：按天（每次最大添加2周）、按周、指定日期维护。是否需要上传维护凭证。
<br />	②计划清单记录：超期清单置顶、按计划时间筛选、按维护时间筛选、按状态筛选。
<br />	③计划任务处理：最大可以提前处理未来10天内的计划运维单子。
<br />	④计划停机时间：开始时间、结束时间、类别。
<br />	(3)点检管理：设备设施点检巡检记录。
<br />	6、看板：
<br />	(1)CAD图形每15秒刷新，已报警位置亮红色、计划超期未维护黄色。
<br />	7、事务/日志查询
<br />	(1)备品备件出入库事务查询
<br />	(2)登陆成功失败查询
<br />	(3)盘点记录查询，按零件查询
<br />	(4)用户变更事务。
<br />	(5)审计明细报表。
<br />	
<br />	
<br />	使用文档用于商业目的，请联系作者购买。
<br />	软件开发中源码：https://github.com/wanglei0803/EAM
<br />	Vx：kaixinsanshi
