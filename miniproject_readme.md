
Image And Video Processing Lab
Mini Project - JPEG Compression


Saurabh Mehra (23EC65R06)
Anshu Pal (23EC65R04)

Problem --
Designing an JPEG Image compression 


Procedure to run --

1) open the code and run it
2) copy the path of image to be compressed
3) enter the scaling factor
4) write the image of output image
5) now copy the path of output image to know the size of output image



Functions

1) rgb_to_ycbcr(r,g,b)
- Takes as input the red, green and blue data stream
- Converts it to y, cb and cr components and returns them

2) dct_coefficient(input_list):
- Finds out the DCT of data stream of input_list

3) dct2_coefficients(matrix)
- finds 2D Fast DCT of the data stream of matrix

4) quantize_matrix(matrix, quantization_matrix)
- Takes as input the data stream matrix and the quantizing matrix qquantization_matrix
- Returns the quantized data stream

5) run_length_encode(zigzag)
- Finds out the run length encoding of the zigzag

6) huffman_code_generator(input_string)
- Finds out the huffman code 

7) encode(input_r, input_g, input_b)
- Performs JPEG Image compression pipeline 





