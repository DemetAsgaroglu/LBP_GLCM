# LBP-GLCM Parmak İzi Analizi

## Açıklama
Bu proje, parmak izi görüntülerinin analizi için **Local Binary Pattern (LBP)** ve **Gray-Level Co-Occurrence Matrix (GLCM)** tekniklerini kullanmaktadır. LBP, bir görüntüdeki dokusal özellikleri çıkarırken; GLCM, piksel yoğunlukları arasındaki ilişkileri analiz etmek için kullanılır.

## Kullanım
1. **Veri Kümesini Hazırlayın**
   - `dataset_path` değişkeni altında belirtilen klasörde `.bmp` uzantılı parmak izi görüntülerini bulundurmalısınız.

2. **Kodları Çalıştırın**
   - Jupyter Notebook ortamında kodları sırasıyla çalıştırarak verileri işleyebilirsiniz.

3. **Özellik Çıkarma**
   - LBP ile doku özellikleri çıkarılır.
   - GLCM ile gri seviyeler arasındaki ilişki hesaplanır.

4. **Sonuçları Görselleştirme**
   - Matplotlib kullanarak LBP görüntüleri ve GLCM analizlerini görselleştirebilirsiniz.

## Örnek Çıktılar
Kodun başarılı şekilde çalıştırılmasının ardından aşağıdaki çıktıları elde edebilirsiniz:
- Taranan parmak izi görüntüleri
- LBP ile elde edilen doku desenleri
- GLCM ile hesaplanan kontrast, enerji, homojenlik gibi metrikler

