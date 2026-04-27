# Module 07

## Exercise: Performance Testing

Screenshot of the performance testings:
1. test_plan_1.jmx
![T1G](./assets/images/test1_gui.png)
![T1C](./assets/images/test1_cli.png)

2. test_plan_2.jmx
![T2G](./assets/images/test2_gui.png)
![T2C](./assets/images/test2_cli.png)

3. test_plan_3.jmx
![T3G](./assets/images/test3_gui.png)
![T3C](./assets/images/test3_cli.png)


## Exercise: Profiling with IntelliJ IDEA
1. Optimizing method getAllStudentWithCourse
   ![Unoptimized Code](./assets/images/prof1_unoptimized_code.png)
   ![Optimized Code](./assets/images/prof1_optimized_code.png)
   Dalam Kode sebelumnya, fungsi `getAllStudentWithCourse` memakan waktu sangat banyak (4.4s) sekarang dengan optimisasi sesuai gambar, fungsi tersebut hanya memerlukan 1.8s, performa aplikasi meningkat drastis, lebih dari 50%.

2. Optimizing method joinStudentNames
   ![Unoptimized Code](./assets/images/prof2_unoptimized_code.png)
   ![Optimized Code](./assets/images/prof2_optimized_code.png)
   Dalam Kode sebelumnya, fungsi `joinStudentNames` memakan waktu sangat banyak (~700ms) sekarang dengan optimisasi sesuai gambar, fungsi tersebut hanya memerlukan ~100ms, performa aplikasi meningkat drastis, lebih dari 50%.

3. Optimizing method findStudentWithHighestGpa
   ![Unoptimized Code](./assets/images/prof3_unoptimized_code.png)
   ![Optimized Code](./assets/images/prof3_optimized_code.png)
   Dalam Kode sebelumnya, fungsi `findStudentWithHighestGpa` memakan lumayan banyak (~150ms) sekarang dengan optimisasi sesuai gambar, fungsi tersebut hanya memerlukan ~55ms, performa aplikasi meningkat drastis, lebih dari 50%.

**Apakah terdapat perbedaan ketika menjalankan JMeter sebelum dan sesudah optimisasi?**
Ya, terdapat perbedaan dalam performanya, setelah optimisasi, program terasa jauh lebih responsif.


