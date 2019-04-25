# K-Means-Anchors

## Usage:

Just run jupyter notebook and replace toy path with your root path that point to annotation files. And it will compute anchor ratios for your train dataset.

The annotation file formate should be like follow:

```
<annotation>
	<folder>3</folder>
	<filename>ocr_20190202_5c55198534963.jpg</filename>
	<path>ocr_20190202_5c55198534963.jpg</path>
	<source>
		<database>Unknown</database>
	</source>
	<size>
		<width>640</width>
		<height>832</height>
		<depth>3</depth>
	</size>
	<segmented>0</segmented>
	<object>
		<name>driving_license</name>
		<pose>Unspecified</pose>
		<truncated>0</truncated>
		<difficult>0</difficult>
		<bndbox>
			<xmin>37</xmin>
			<ymin>318</ymin>
			<xmax>562</xmax>
			<ymax>664</ymax>
		</bndbox>
	</object>
</annotation>
```
## Note

I am sorry for that I forgot some repositories which some codes came from, pls make a pull request if you knows. Thank u.