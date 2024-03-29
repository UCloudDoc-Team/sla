

# 云硬盘 UDisk 服务等级协议（SLA）

UCloud UDisk服务等级协议（以下简称“本协议”）是规定了UCloud向客户提供UCloud
UDisk云硬盘服务的一般性服务等级指标和服务注意事项。本协议是《UCloud用户协议》、《云服务法律声明及隐私条款》的补充。您通过盖章、网络页面点击确认或以其他方式（如点击确认同意用《UCloud用户协议》）选择接受本协议，即表示您与本公司已达成协议并同意接受本协议的全部约定内容。如若双方盖章文本与网络页面点击确认或以其他方式选择接受之服务条款文本，存有不一致之处，以双方盖章文本为准。在接受本协议之前，请您仔细阅读本协议的全部内容。您阅读后，如果继续使用UDisk服务，即表示您接受本协议并同意受其约束；如果您不同意本协议，您可以选择不使用UDisk服务。

## 1、数据存储的持久性

1.1
UDisk云硬盘数据存储的持久性：普通云硬盘数据持久性为99.99999%，SSD云硬盘和RSSD云硬盘数据持久性为99.999999%。

1.2
数据存储的持久性定义：合同期内数据保持存储状态不丢失的概率。持久性为99.999999％意指合同期内用户每月100000000字节的数据，合同期内每月数据不丢失的概率为99.999999%，即每月只有1字节的数据丢失的可能性。以自然月为统计周期，不满一个月按一个月计。

## 2、数据可销毁性

2.1 在您要求删除数据或设备在弃置、转售前，UCloud将通过高级清零操作彻底删除用户所有数据且无法复原，并对报废硬盘做消磁处理。

2.2
用户数据彻底删除的场景不包括在取得UCloud同意后，UCloud为未及时续费用户的数据保留7天的情形，以防止用户由于某些原因无法及时续费导致重要数据被删除。

## 3、数据可迁移性

3.1 本公司承诺用户能够控制云硬盘中数据的迁移，保证启用或弃用该云服务时，数据能迁入和迁出。

3.2 本公司在用户迁入迁出时提供相应的工具和技术手段，与用户现有的数据格式保持最大的兼容性。具体导入导出操作步骤请参见帮助说明。

## 4、数据私密性

4.1 UCloud采用了有效的隔离方法，保证同一资源池用户数据互不可见。

4.2 云硬盘根据帐号进行隔离，通过网络隔离的技术保证不同用户间的硬盘和数据互不可见，无法通过内网访问。

4.3
在未经用户授权的情况下，UCloud承诺不会查看用户云硬盘上的数据等。但是UCloud有权从外部监控用户的云硬盘的运行数据，包括吞吐量、IOPS等。为了便于运维和问题排查，UCloud保留查看云硬盘用户操作记录的权利。

4.4 在未经用户授权或非政府机构要求下，UCloud不会查看用户数据。运维人员相关操作会进行详细的记录，有日志进行查询。

## 5、数据知情权

5.1
您可在产品管理中心控制台到云硬盘所在的数据中心可用区名称，您可选择您所需要的数据中心可用区。数据中心物理位置参照网站数据中心说明页面例如，华北一可用区B位于北京市。

5.2 云硬盘的数据会在云硬盘所在的数据中心有三份拷贝，为热备份。

5.3 所有数据中心应遵守当地法律和中华人民共和国法律。

5.4
除政府监管部门监管审计需要或配合安全取证调查外，未经客户同意，不能将用户数据非法提供给任何第三方。为了保障您使用本服务的安全性以及不断改进服务质量的需要，本公司将记录并保存您登录和使用本服务的相关行为日志，不会对外呈现用户个人信息数据。

## 6、 业务可审查性

6.1
根据国家的法律法规要求，为配合政府监管部门的监管审查，合规或取证调查等，本公司可提供您运行在云服务上业务的相关的信息，如关键组件的运行日志、运维人员的操作记录。

## 7、业务功能

7.1 UCloud
UDisk提供给用户的服务功能为www.ucloud.cn 网站所展示的云硬盘服务，完整的功能介绍和操作说明详见产品使用手册和帮助说明。

7.2 UCloud若更换服务的版本或功能会及时通过短信、邮件或网站等方式通知您，以便您能及时做出相应的调整。

## 8、业务可用性

8.1 本公司向您承诺UDisk云硬盘的服务可用性为99.95％。如果服务可用性没有达到承诺，将按照服务赔偿条款进行赔付。

8.2
服务可用性定义：合同期内用户每月云服务业务可用时间的概率，即每月实际可用时间／每月（实际可用时间＋不可用时间）。其中不可用时间的定义为从用户无法使用云服务起至云服务恢复正常水平结束，以自然月为统计周期，不满一个月按一个月计，以分钟为单位。可用性为99.95％指单个用户每月云服务业务可用时间应至少为30天\*24小时\*60分钟\*99.95%=
43178.4分钟，即每月最多存在30天\*24小时\*60分钟\*100%-
431875.4=21.6分钟的不可用时间。云服务业务不可用的统计单元为单个云硬盘实例，云服务业务不可用时间达到1分钟以上算作一次不可用，计入不可用时间，不可用时间若低于1分钟则不计入不可用时间。

## 9、业务资源调配能力

9.1 UDisk实例支持在线升级扩展，单位为GB，具体资源范围和资费详见订单页面展示；

## 10、故障恢复能力

10.1 通过故障监控、快速定位、自动化恢复、告知等一系列故障管控体系，保证云服务的故障恢复能力。

## 11、云硬盘性能指标

11.1 您可购买的单台UDisk普通云硬盘支持10GB\~8000GB，SSD云硬盘支持10GB\~4000GB。

11.2 用户可以得到24000的IOPS（SSD云硬盘）或3000的IOPS（普通型云硬盘）。

## 12、服务计量准确性

12.1
UCloud有准确的计量计费系统，计费方式可以根据约定按年、按月、按时计费。块存储以存储量、硬盘类型计费。以计费页面公布的当时有效的计费模式和标准为准。

## 13、服务变更、终止条款

13.1.
如需停止使用本服务，您须至少提前30天告知本公司，本公司会将您已支付但未消耗的款项尽数返还。对于未提前告知停止使用本服务且未及时续费的用户，如无特殊约定本公司将保留其数据7天。

13.2.本公司承诺，若不再提供某种服务时，提前30天在www.ucloud.cn 上通告或以发网站内通知或书面通知的方式通知您转移业务。届时本公司将退还您已支付但未消耗的款项。

## 14、服务赔偿条款

14.1.
如无其他线下协议，本公司承诺，如可用性没有达到服务等级承诺，则会赔付等同于损失时间的相同时长。对于您自身操作不当导致的可用性不达标，本公司不承担赔偿责任。

14.2. 系统因下列状况无法正常运作，使您无法使用各项服务时，本公司不承担损害赔偿责任，该状况包括但不限于：  
（1）本公司在本网站公告的系统停机维护期间；

（2）电信设备出现故障不能进行数据传输的；

（3）因台风、地震、海啸、洪水、停电、战争、恐怖袭击等不可抗力之因素，造成本公司系统障碍不能执行业务的；

（4）黑客攻击、电信部门技术调整或故障、网站升级、银行方面的问题等原因而造成的服务中断或者延迟。

## 15、用户约束条款

15.1. 您有权享受 UCloud 提供的互联网技术和信息服务，并有权在接受 UCloud 提供服务的期间获得 UCloud
的技术支持、咨询等服务，服务内容详见 UCloud 相关产品介绍。

15.2. 您保证不会利用技术或其他手段破坏及扰乱 UCloud 网站以及 UCloud 其他客户的网站。

15.3. 您保证尊重 UCloud 及其他第三方的知识产权和其他合法权利，并保证在发生侵犯该等权益的违法事件时尽力保护 UCloud
及其雇员、合伙伙伴等免于因该等事件受到影响或损失；侵权行为一旦发生，UCloud
保留终止向您提供服务并不退还任何款项的权利。

15.4. 对由于您向 UCloud 提供的联络方式有误而导致的一切损失，由您自行承担，该损失包括但不限于因您未能及时收到 UCloud
的相关通知而导致的后果和损失。

15.5. 您保证在使用 UCloud 服务时将遵守国家、地方法律法规、行业惯例和社会公共道德，不会利用 UCloud
提供的服务进行存储、发布、传播如下信息和内容：违反国家法律法规政策的任何内容（信息）；违反国家规定的政治宣传和/
或新闻信息；涉及国家秘密和/或安全的信息；封建迷信和/或淫秽、色情、下流的信息或教唆犯罪的信息；博彩有奖、赌博游戏；违反国家民族和宗教政策的信息；防碍互联网运行安全的信息；侵害他人合法权益的信息和/或其他有损于社会秩序、社会治安、公共道德的信息或内容。您同时承诺不得为他人发布上述不符合国家规定和/或本服务条款约定的信息内容提供任何便利，包括但不限于设置URL、BANNER链接等。您同意
UCloud 有权在您违反上述约定时有权终止向您提供服务并不予退还任何款项，因您上述行为给 UCloud 造成损失的，您应予以赔偿。

## 16、UCloud 免责条款

因以下原因导致的服务不可用，UCloud不承担任何责任：

16.1 UCloud预先通知客户后进行系统维护所引起的，包括割接、维修、升级和模拟故障演练；

16.2 任何UCloud所属设备以外的网络、设备故障或配置调整引起的；

16.3 客户的应用程序受到黑客攻击而引起的；

16.4 客户维护不当或保密不当致使数据、口令、密码等丢失或泄漏所引起的；

16.5 客户的疏忽或由客户授权的操作所引起的；

16.6 客户未遵循UCloud产品使用文档或使用建议引起的；

16.7 由于客户违反《UCloud用户协议》导致的服务被暂停或终止，包括由于欠费导致云硬盘被暂停服务或被释放等；

16.8
其他不可抗力因素引起的。不可抗力以及意外事件是指由于信息网络正常的设备维护，信息网络连接故障，电脑、通讯或其他系统的故障，电力故障，战争，天灾，政府行为等一切不能预见、不可避免、不能克服的自然、社会现象客观情况。
