## Chr Find N

</br>

##### 🙈: **禹开权**

##### 📧: **1962568272**[@qq.com](/qq.com)

</br>

### Description

This is a simple program that finds the N character in a string. It is licensed under the MIT license.

</br>

### windowse 10/11 Usage

#### download

chr_findn.exe is in the release folder

```
./chr_findn.exe test.fasta test.bed
```

### Linux Usage

#### download

chr_findn is in the release folder

```
./chr_findn test.fasta test.bed
```

</br>

### Example

#### Input

test.fasta

```
>chr1
ATNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNN
NNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNN
NNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNtaaattgttt
taaattgtttctgtttgcagttgacatgatctNNNNNatagaaaacacca
ataactctgccaaaaaatttagaattcataaatgaatttagtaaagttgc
>chr2
NNNNNNNNNNNNNNNTTNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNN
NNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNN
NNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNtaaattgttt
taaattgtttctgtttgcagttgacatgatcttatatatagaaaacacca
ataactctgccaaaaaatttagaattcataaatgaatttagtaaagttgc
```

#### Output

test.bed

```
chr1	3	140
chr1	183	187
chr2	1	15
chr2	18	140

```
