# KNIME-variants-of-outlier-detection
## 02 illustrating outlier calculation mathematically
using the k-parameterized R InterQuartil Range (IQR) (first-third quartil) R = [Q1 - k(IQR), Q3 + k(IQR)] with IQR = Q3 - Q1 and k >= 0 outliers in small data sets are hard to detect. Implementing another approach with a k=3 k-Means cluster helps to resolve this "issue".
