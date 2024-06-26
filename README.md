# Police Car Chase with Extended Kalman Filter

## Problem Statement

## Abstract

## Plan of Action
1. Overview
2. Process Model
3. Prediction Step
4. Measurement
5. Update Step
6. The Chase

-------------

## 1. Overview

<p align="center">
  <img src="https://github.com/yudhisteer/Police-Car-Chase-with-Extended-Kalman-Filter/assets/59663734/be71cc3e-f1f9-4c9f-b0a5-7bb7376092b5" width="60%" />
</p>

<p align="center">
  <img src="https://github.com/yudhisteer/Police-Car-Chase-with-Extended-Kalman-Filter/assets/59663734/bafe2729-ecee-492b-a5c2-2b6fb6e66c0b" />
</p>


<div align="center">
    <table>
        <tr>
            <th></th>
            <th>Linear Kalman Filter</th>
            <th>Extended Kalman Filter</th>
        </tr>
        <tr>
            <th>Process model:</th>
            <td><img src="https://github.com/yudhisteer/Police-Car-Chase-with-Extended-Kalman-Filter/assets/59663734/d4e0430e-3809-40ba-ab25-d37a537a3f76" alt="Linear Kalman Filter"></td>
            <td><img src="https://github.com/yudhisteer/Police-Car-Chase-with-Extended-Kalman-Filter/assets/59663734/2d67cfdd-6c42-4d10-9284-5eba74161915" alt="Extended Kalman Filter"></td>
        </tr>
        <tr>
            <th>Measurement:</th>
            <td><img src="https://github.com/yudhisteer/Police-Car-Chase-with-Extended-Kalman-Filter/assets/59663734/6a88678a-d0b8-4f83-a6a1-a748768ed5c1" alt="Measurement 1"></td>
            <td><img src="https://github.com/yudhisteer/Police-Car-Chase-with-Extended-Kalman-Filter/assets/59663734/5ce7def9-3309-4dd0-91f5-7cfcc92ce380" alt="Measurement 2"></td>
        </tr>
    </table>
</div>

<div style="text-align: center;">
    <table>
        <tr>
            <th align="center">True State:</th>
            <td align="center"><img src="https://github.com/yudhisteer/Police-Car-Chase-with-Extended-Kalman-Filter/assets/59663734/9c1554de-2a53-4aff-88fe-896c7426f12b" alt="Image 1"></td>
        </tr>
        <tr>
            <th align="center">Estimated State:</th>
            <td align="center"><img src="https://github.com/yudhisteer/Police-Car-Chase-with-Extended-Kalman-Filter/assets/59663734/575b75fb-19df-4c84-97c2-945feaa59042" alt="Image 2"></td>
        </tr>
        <tr>
            <th align="center">Estimation Error:</th>
            <td align="center"><img src="https://github.com/yudhisteer/Police-Car-Chase-with-Extended-Kalman-Filter/assets/59663734/f575d765-911f-45f0-92af-1038c855f521" alt="Image 3"></td>
        </tr>
    </table>
</div>




<div align="center">
    <table>
        <tr>
            <th>a priori State:</th>
            <td><img src="https://github.com/yudhisteer/Police-Car-Chase-with-Extended-Kalman-Filter/assets/59663734/1e7843a4-2aca-4ea7-9246-5ca2af7dffeb" alt="Image 1"></td>
        </tr>
        <tr>
            <th>a posteriori State:</th>
            <td><img src="https://github.com/yudhisteer/Police-Car-Chase-with-Extended-Kalman-Filter/assets/59663734/3438e841-b573-4e92-9b23-47d57c191762" alt="Image 2"></td>
        </tr>
    </table>
</div>


<div align="center">
    <table>
        <tr>
            <th>a priori Covariance:</th>
            <td><img src="https://github.com/yudhisteer/Police-Car-Chase-with-Extended-Kalman-Filter/assets/59663734/9678e46c-4ffa-426e-9d67-2404cba55cd5" alt="Image 1"></td>
        </tr>
        <tr>
            <th>a posteriori Covariance:</th>
            <td><img src="https://github.com/yudhisteer/Police-Car-Chase-with-Extended-Kalman-Filter/assets/59663734/c62157ef-33d5-4742-aaa0-109702c196d0" alt="Image 2"></td>
        </tr>
    </table>
</div>







----------

## 2. Process Model

<div align="center">
    <table>
        <tr>
            <th>Linear Kalman Filter</th>
            <th>Extended Kalman Filter</th>
        </tr>
         <tr>
            <th>2D Linear Constant Velocity Model</th>
            <th>2D Non-Linear Constant Velocity Model</th>
        </tr>
        <tr>
            <td><img src="https://github.com/yudhisteer/Police-Car-Chase-with-Extended-Kalman-Filter/assets/59663734/6a2e861a-95c1-4b9f-8dfd-dbfc7ace9efb" width="72%"  alt="Image 1"></td>
            <td><img src="https://github.com/yudhisteer/Police-Car-Chase-with-Extended-Kalman-Filter/assets/59663734/557eb6a0-b5ef-4703-9ebb-d1917a2e294e" alt="Image 1"></td>
        </tr>
        <tr>
            <td><img src="https://github.com/yudhisteer/Police-Car-Chase-with-Extended-Kalman-Filter/assets/59663734/3ddb7fa3-b29d-4bc9-a909-7964229153a9" alt="Image 5"></td>
            <td><img src="https://github.com/yudhisteer/Police-Car-Chase-with-Extended-Kalman-Filter/assets/59663734/c95ad0af-43da-4d4c-8b9c-e421c2e4bae8" alt="Image 6"></td>
        </tr>
    </table>
</div>

--------

## 3. Prediction Step


----------

## References
1. https://courses.cs.washington.edu/courses/cse571/23sp/
2. https://codingcorner.org/extended-kalman-filter-explained/
3. https://www.youtube.com/watch?v=DE6Jn2cB4J4&t=2048s
4. https://medium.com/towards-data-science/extended-kalman-filter-43e52b16757d
5. https://zlthinker.github.io/extended_kalman_filter
6. https://www.alanzucconi.com/2022/07/24/extended-kalman-filter/
7. https://github.com/balzer82/Kalman
8. https://automaticaddison.com/extended-kalman-filter-ekf-with-python-code-example/
9. https://github.com/rlabbe/Kalman-and-Bayesian-Filters-in-Python/blob/master/11-Extended-Kalman-Filters.ipynb
10. 
