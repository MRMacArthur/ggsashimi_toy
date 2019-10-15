# ggsashimi_toy
A toy example of ggsashimi for troubleshooting

Running the following command successfully outputs png image
`~/sashimi-plot.py -b toyBamFiles.txt -g Cel_transcriptGTF.gtf -M 10 -C 3 -O 3 --shrink --alpha 0.05 --base-size=20 --ann-height=4 --height=3 --width=18 -F png -P palette.txt -c II:9358531-9369098`

But adding the aggregation tag (-A mean) throws the following error
`Error in j[4] <- as.numeric(d[x == j[2] + 1, y]) :
  replacement has length zero`

