<!--
 * @Author: yuhao_lian lianyuhao@ieee.org
 * @Date: 2025-04-01 21:06:31
 * @LastEditors: yuhao_lian lianyuhao@ieee.org
 * @LastEditTime: 2025-04-06 19:00:20
 * @FilePath: \information_lyh\src\views\HomeView.vue
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
<script setup>
import '../style/styles.css'
import '../style/pygment_trac.css'
</script>

<template>
  <main>
      <div class="wrapper">
      <header>
        <h1>
          <a href="https://www.piggylyh.cn/">连宇昊 （Yuhao Lian）</a>
        </h1>
        <img src="../assets/data/setfie.png" alt="Logo" />
        <p>
          <br>连宇昊于2024年6月在中国重庆的<strong>重庆邮电大学通信与信息工程学院</strong>获得<strong>工学荣誉学士学位</strong>。目前，正在中国杭州的<strong>浙江大学</strong>攻读<strong>电子信息专业硕士学位</strong>。他的研究方向包括B5G/6G无线通信（OFDM-IM通信系统、面对更多接入设备的非正交多址接入技术）与低空经济下的反无人机技术（基于深度学习与信号处理的射频识别）。<br>
          <br><strong>Phone:</strong> +86 18334564608<br>
          <strong>E-mail:</strong> Yuhao_lian@zju.edu.cn<br>
          &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbspLianyuhao@ieee.org<br>
          <strong>Address:</strong> Zhejiang University, Hangzhou, China<br>


          <br><strong><a href="https://github.com/YuhaoLian" target="_blank">GitHub&nbsp&nbsp </a></strong>
          <strong><a href="https://scholar.google.com/citations?hl=zh-CN&user=dlzoXeQAAAAJ"
              target="_blank">Google Scholar&nbsp&nbsp</a></strong>
          <strong><a href="../assets/data/CV_YuhaoLian.pdf" target="_blank">CV 个人简历</a></strong>
        </p>
      </header>

      <section>
        <h1>个人自述 Bibliograph</h1>
        <p>本人目前攻读浙江大学工程师学院新一代电信技术专业硕士，并隶属于浙江大学NESC工控所，拥有重庆邮电大学的荣誉学士学位。本科期间，GPA：3.75/4.0，综合成绩专业排名：1/241，平均成绩专业排名：1/241，必修加权成绩：91.3，在信号与系统(98)、通信原理(92)、信息论(98)、高等数学(99/98)、概率论 (97)等主修课程中取得优异的成绩。 与此同时，本科深耕B5G/6G无线通信领域，科研方面得到了谢显中、郭磊教授与邓明亮、鲜永菊副教授的指导。
        </p>

        <hr style="FILTER: alpha(opacity=100,finishopacity=0,style=3)" width="95%" color=#987cb9 SIZE=3>
        <h1>研究方向 Research</h1>

        <p>低空经济的无人机射频识别与面对更多接入的非正交多址接入技术</p>

        <h2>项目 Project</h2>

        <h3>面向更多接入设备的非正交多址接入技术 (1月. 2023 - Now)
        </h3>
        <ul>
          <li> 针对大规模接入的无线场景与需要更多接入组数的灵活PON场景。</li><br>
          <table style="width: 95%; table-layout: fixed;">
            <tbody>
              <tr>
                <td style="width: 25%; text-align: center;">
                  <img src="../assets/data/fig/弹性PON图2.png" border="0" style="width: 100%; display: block; margin: 0 auto;">
                </td>
                <td style="width: 70%; text-align: center;">
                  <img src="../assets/data/fig/弹性 PON.png" border="0" style="width: 100%; display: block; margin: 0 auto;">
                </td>
              </tr>
            </tbody>
          </table>
          <li>为了降低串行干扰，基于信号的施密特正交化提出了星座稀疏叠加的非正交接入方式，从理论上可以突破传统的接入设备极限。</li>
          <li>通过 Matlab 与 VPI 联合仿真 与 AWG 与 DPO 实机实验得到验证。</li><br>
          <table style="width: 95%; table-layout: fixed;">
            <tbody>
              <tr>
                <td style="width: 30%; text-align: center;">
                  <img src="../assets/data/fig/PD-SDCMA.png" border="0" style="width: 100%; display: block; margin: 0 auto;">
                </td>
                <td style="width: 65%; text-align: center;">
                  <img src="../assets/data/fig/constelation.png" border="0" style="width: 100%; display: block; margin: 0 auto;">
                </td>
              </tr>
            </tbody>
          </table>
        </ul>
        <h3>基于机器学习的热电机组氮氧化物排放动态预测 (10月. 2024 - Now)
        </h3>
        <ul>
          <li>为了相应双碳目标，对于CFB中的NO_x的预测进行建模，解决出口NOx浓度测量滞后性大的问题。</li>
          <li>在语义嵌入的基础上提出了AML-XGBoost-Ts模型，在实现NOx浓度及时预测的同时提升XGBoost数据建模的可解释性。 </li><br>
          <table>
            <tbody>
              <tr>
                <td style="text-align: center;">
                  <img src="../assets/data/fig/NOx.png" border="0" style="width: 90%; display: block; margin: 0 auto;">
                </td>
            </tr>
            </tbody>
          </table>
          <li>构建基于SHAP值的可解释性分析框架，实现预测结果验证。</li><br>
        </ul>


        <h3>Digital Communications—OFDM-IM (10月. 2022 - 1月，2024)
        </h3>
        <ul>
          <li>Supervisor: <a href="https://eng.ox.ac.uk/people/justin-coon/" target="_blank">
              Prof. Justin Coon </a> (Oxford University)
          </li>
          <li>针对OFDM-IM系统，在不同参数设置下展开了深入的仿真研究，以评估系统性能。</li>
          <li>创新性地采用WHT（Walsh-Hadamard Transform）与双WHT技术，有效降低了OFDM-IM系统的高PAPR问题。</li><br> 
          <table>
            <tbody>
              <tr>
                <td style="text-align: center;">
                  <img src="../assets/data/fig/OFDM-IM-WHT.png" border="0" style="width: 95%; display: block; margin: 0 auto;">
                </td>
            </tr>
            </tbody>
          </table>
          <li>通过对现有OFDM-IM检测算法的分析与改进，提出了一种基于功率阈值的低信噪比检测方法，增强了系统的抗干扰能力。</li><br> 
          <table>
            <tbody>
              <tr>
                <td style="text-align: center;">
                  <img src="../assets/data/fig/OFDM-IM-MSP.png" border="0" style="width: 95%; display: block; margin: 0 auto;">
                </td>
            </tr>
            </tbody>
          </table>
        </ul>

    <h3> 基于数字孪生模型的城市应急车辆路线仿真研究 (5月. 2022 - 4月，2024)
        </h3>
        <ul>

          <li>针对特种车辆（救护车/消防车等）在城市拥堵环境中的通行效率问题，主导设计了一套基于实时交通态势的智能调度系统。</li>
          <li>创新性地构建了"拥堵指数-警力效能"双目标优化模型，融合实时路况数据、警力分布热力图和应急事件等级，运用启发式算法实现道路节点通行能力与警员处置能力的动态适配。</li><br>
          <table>
            <tbody>
              <tr>
                <td style="text-align: center;">
                  <img src="../assets/data/fig/V2X.png" border="0" style="width: 95%; display: block; margin: 0 auto;">
                </td>
            </tr>
            </tbody>
          </table>
        </ul>



        <h2>科研产出 Publications</h2>

        <h3>学术会议 Conference Papers</h3>
        <ul>
          <li><strong>Y. Lian</strong>, Z. Li, Y. Li and  C.Liu, "Power Domain Sparse Dimensional Constellation Multiple Access (PD-SDCMA): A Novel PD-NOMA for More Access Users", <em>2025 Vehicular Technology Conference fall (VTC-Fall)</em> (Submission) </li>
          <li><strong>Y. Lian</strong>, X. Deng, X .Dou and X .Han, "PowerDomain SparseDimensional Constellation Multiple Access (PD-SDCMA) for Enabled Flexible PONs", <em>2025 IEEE/CIC International Conference on Communications in China (ICCC)</em> (Submission) </li>
          <li><strong>Y. Lian</strong>, M. Ying, S. Wang and Y. Wang, "An Efficient Maximum Subcarrier Power Detection Scheme for OFDM-IM Systems," <em>2023 International Wireless Communications and Mobile Computing (IWCMC)</em>, Marrakesh, Morocco, 2023, pp. 258-263</li>
          <li><strong>Y. Lian</strong>, M. Ying, S. Wang and Y. Wang, "An Efficient Fast Walsh-Hadamard Transform Based OFDM-IM Scheme with Lower PAPR," <em>2023 Wireless Telecommunications Symposium (WTS)</em>, Boston, MA, USA, 2023, pp. 1-6 </li>
          <li><strong>Y. Lian</strong>, X. Bi, P. Zhao and Y. Jiang, "A Research on Modulation and Detection in OFDM-IM System," <em>2023 3rd Asia-Pacific Conference on Communications Technology and Computer Science (ACCTCS)</em>, Shenyang, China, 2023, pp. 27-33 </li>
          <li><strong>Y. Lian</strong>, Y. Wang, X. Lin. "Double Walsh-Hadamard Transform for Improved Efficiency in OFDM-IM."  <em>Proceedings of the 12th International Conference on Communications, Circuits, and Systems (ICCCAS)</em>, Lecture Notes in Electrical Engineering, vol 1193. Springer, Singapore.  </li>
          <li>X. Deng, <strong>Y. Lian</strong>, J. Lu, H. Liu, Y. Pan and H. Chen, " <em>Emergency Vehicle Road Congestion Evacuation System Based on the Internet of Vehicles," 2023 6th International Conference on Electronics Technology (ICET)</em>, Chengdu, China, 2023, pp. 517-522</li>
          <li>Y. Wang and <strong>Y. Lian</strong>, "MLFEN: Multi-scale Long-Distance Feature Extraction Network,"" <em>Lecture notes in computer science</em>, pp. 189–199, Jan. 2023  </li>
          <li>Y. Wang and <strong>Y. Lian</strong>, "ZPF-DLSTM: An Efficient Deep Network with Low Time Latency," <em>Studies in computational intelligence</em>, pp. 73–85, Jan. 2024  </li>
        </ul>

        <h3>期刊 Journal Articles</h3>
        <ul>
          <li>Y. Wang, <strong>Y. Lian</strong>, M. Ying and S. Wang, "Attention Multilayer Perceptron Fusion Network," in <em>IEEE Access</em>, vol. 11, pp. 83580-83588, 2023</li>
        </ul>

        <h3>专利 Patents</h3>
        <ul>
          <li><strong>连宇昊</strong>,邓鑫茂,卢嘉煜,等.一种基于车联网的紧急车辆道路拥堵疏散系统:CN202310596896.3[P].CN116631211A[2025-04-06]</li>
        </ul>

        <h3>软件著作权 Software Copyrights</h3>
        <ul>
          <li>杨金贺, 欧洪林, 陈秋雨, <strong>连宇昊</strong>. 在线自动化审批管理系统 V1.0 [计算机程序]. 重庆邮电大学, 2023-03-22.</li>
        </ul>




        <hr style="FILTER: alpha(opacity=100,finishopacity=0,style=3)" width="95%" color=#987cb9 SIZE=3>
        <h1>个人荣誉 Awards</h1>
        <h4>
          2022年国家奖学金<br>
          2023年国家奖学金<br>
          学业一等奖学金x3<br>
          重庆市国家奖学金代表 <a href="https://www.cqrb.cn/quanweifabu/2024-06-28/1960400_pc.html" target="_blank">重庆日报</a><br>
          重庆市青少年科技创新市长提名奖 <a href="https://www.cq.gov.cn/zwgk/zfxxgkml/szfwj/qtgw/202402/t20240204_12900213.html" target="_blank">重庆市政府</a><br>
          2022年高教社杯全国大学生数学建模竞赛国家一等奖<a href="https://www.mcm.edu.cn/upload_cn/node/629/uJzoCRK40ebedd130f42ed41e5f144ac29bae490.pdf" target="_blank">CUMCM</a><br>
          2023年互联网+大学生创新创业大赛铜奖x2<a href="https://cy.ncss.cn/" target="_blank">互联网+</a><br>
          2024年互联网+大学生创新创业大赛进入总决赛<a href="https://cy.ncss.cn/" target="_blank">互联网+</a><br>
          2024年重庆邮电大学五四之星（校内最高荣誉）
          ...
        </h4>

        <br>
        <br>
        <hr style="FILTER: alpha(opacity=100,finishopacity=0,style=3)" width="95%" color=#987cb9 SIZE=3>
      </section>
      <footer>
        <p><Small>光芒万丈！</Small></p>
      </footer>
    </div>
  </main>
</template>
