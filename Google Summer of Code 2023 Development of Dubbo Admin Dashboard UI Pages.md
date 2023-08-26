# Google Summer of Code 2023: Development of Dubbo Admin Dashboard UI Pages

## Project Goal

The overall goal is to complete the upgrade of the project framework and dependencies, and then improve the project engineering, and complete the timeout period, call retry, same area priority, weight ratio, parameter routing, call degradation, access log, traffic The front-end development and implementation of modules such as grayscale and fixed machine diversion, and the development of large-screen tasks on the home page have also been realized.

## My Contributions

1. Upgraded of the project framework and engineering of the project

   ![image-20230827072817285](C:\Users\wys\AppData\Roaming\Typora\typora-user-images\image-20230827072817285.png)

   

2. Complete the front-end development and implementation of modules such as timeout, call retry, same-region priority, weight ratio, parameter routing, call degradation, access log, traffic grayscale, and fixed machine diversion.

   ![image-20230827073349070](C:\Users\wys\AppData\Roaming\Typora\typora-user-images\image-20230827073349070.png)

3. Complete the design and implementation of the large screen on the home page, and display the overall data of Dubbo services on the large screen.

   ![img](https://user-images.githubusercontent.com/91682295/257093656-8e986a9c-6865-4fa3-a084-6d1d80327912.png)

   ![img](https://user-images.githubusercontent.com/91682295/257093688-8225e59a-e7be-4ee7-8a0d-73643e026842.png)

4. Formulate and improve the creation of routing rules.  Detailed link [here](https://cn.dubbo.apache.org/zh-cn/overview/tasks/traffic-management/timeout/).

5. The addition of engineering service mock function and jest unit test function makes the project more engineering-oriented.

## My Works Links

### Pull Request

| PR                                                       | Description                                                  |
| -------------------------------------------------------- | ------------------------------------------------------------ |
| [#1114](https://github.com/apache/dubbo-admin/pull/1114) | test: Add unit tests for the front end                       |
| [#1122](https://github.com/apache/dubbo-admin/pull/1122) | fix: Several requirements and small adjustments for the current front end |
| [#1128](https://github.com/apache/dubbo-admin/pull/1128) | fix: After the conditional path is successfully created, the popup window does not close automatically |
| [#1129](https://github.com/apache/dubbo-admin/pull/1129) | fix: Dynamic configuration, the front-end page does not display the list and adds mock function |
| [#1137](https://github.com/apache/dubbo-admin/pull/1137) | feat: Routing rules page, add a jump link to the official website description and initialize some pages |
| [#1160](https://github.com/apache/dubbo-admin/pull/1160) | feat： Add six traffic function pages                        |
| [#1171](https://github.com/apache/dubbo-admin/pull/1171) | feat: add TrafficGay 、TrafficWeight and fix: some problems  |
| [#1193](https://github.com/apache/dubbo-admin/pull/1193) | fix: fix some issues                                         |
| [#1206](https://github.com/apache/dubbo-admin/pull/1206) | feat：add Cluster overview pages                             |

## Next

I will continue to participate in Dubbo Admin related contributions. According to Dubbo Admin's next plan, I will continue to participate in the development tasks of Dubbo control plane and Nodejs development of Dubbo.

Thank you for being a part of this wonderful summer.

—— Yongshuai Wang