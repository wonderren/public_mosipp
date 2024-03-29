# public_mosipp

C++ Implementation of Multi-Objective Safe-Interval Path Planning

The code is distributed for academic and non-commercial use. THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

<p align="center">
<img src="https://github.com/wonderren/wonderren.github.io/blob/master/images/fig_mosipp.gif" alt="" hspace="15" style=" border: #FFFFFF 2px none;">
</p>

(Fig 1: A visualization of a set of Pareto-optimal collision-free paths for the robot (red dot) among both static and dynamic obstacles moving along known trajectories. Green circles are areas with communication and moving outside incurs a large penalty cost. The robot needs to arrive early while minimizing the communication penalty cost.)

## Usage

### Compile and toy example

- (cd to the folder of this repo public_mosipp/)

- mkdir build

- cd build

- cmake ..

- make

- ./test_mosipp

### Notes

- The file test_mosipp.cpp provides a toy example about how to use the code (declare graphs and costs, invoke the planner, get the result).

## References

[1] Ren, Zhongqiang, Sivakumar Rathinam, Maxim Likhachev, and Howie Choset. "Multi-Objective Safe-Interval Path Planning With Dynamic Obstacles." IEEE Robotics and Automation Letters 7, no. 3 (2022): 8154-8161.\
[[Bibtex](https://wonderren.github.io/files/bibtex_ren22mosipp.txt)]
[[Paper](https://github.com/wonderren/wonderren.github.io/blob/master/files/ren22_mosipp_RAL_IROS22.pdf)]
