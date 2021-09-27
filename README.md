# Pandas-Challenge


For this challenge, I analyzed trends in the data for standardized testing reults in a school district. I think the biggest take away from the data is that charter schools are on average doing 37% less likely to pass both reading and math than dictrict students in standarized testing. This is while spending far less than district school. Which leads to my second takeaway, which is that more money per student does not necessarily equal better grades. Although there appears to be a sweet spot where grades are increase by greater spending, after this spots grades rapidly decline with increasing spending. This leads me to wonder whether the spending per student can be truly said to be accurate (I would want to look at how each school spent their budget to see if the money is really adding value to childs education.) Prehaps Charters are just more efficient with their money causing a greater real spending per student.
```python
	School ID	school_name	type	size	budget	average_reading_score	average_math_score	money_per_student	% Passed Reading	% Passed Math	% Passed
0	0	Huang High School	District	2917	$1,910,635.00</td> <td>81.182722</td> <td>76.629414</td> <td>$655.00	81.316421	65.683922	53.513884
1	1	Figueroa High School	District	2949	$1,884,411.00</td> <td>81.158020</td> <td>76.711767</td> <td>$639.00	80.739234	65.988471	53.204476
2	2	Shelton High School	Charter	1761	$1,056,600.00</td> <td>83.725724</td> <td>83.359455</td> <td>$600.00	95.854628	93.867121	89.892107
3	3	Hernandez High School	District	4635	$3,022,020.00</td> <td>80.934412</td> <td>77.289752</td> <td>$652.00	80.862999	66.752967	53.527508
4	4	Griffin High School	Charter	1468	$917,500.00</td> <td>83.816757</td> <td>83.351499</td> <td>$625.00	97.138965	93.392371	90.599455
5	5	Wilson High School	Charter	2283	$1,319,574.00</td> <td>83.989488</td> <td>83.274201</td> <td>$578.00	96.539641	93.867718	90.582567
6	6	Cabrera High School	Charter	1858	$1,081,356.00</td> <td>83.975780</td> <td>83.061895</td> <td>$582.00	97.039828	94.133477	91.334769
7	7	Bailey High School	District	4976	$3,124,928.00</td> <td>81.033963</td> <td>77.048432</td> <td>$628.00	81.933280	66.680064	54.642283
8	8	Holden High School	Charter	427	$248,087.00</td> <td>83.814988</td> <td>83.803279</td> <td>$581.00	96.252927	92.505855	89.227166
9	9	Pena High School	Charter	962	$585,858.00</td> <td>84.044699</td> <td>83.839917</td> <td>$609.00	95.945946	94.594595	90.540541
10	10	Wright High School	Charter	1800	$1,049,400.00</td> <td>83.955000</td> <td>83.682222</td> <td>$583.00	96.611111	93.333333	90.333333
11	11	Rodriguez High School	District	3999	$2,547,363.00</td> <td>80.744686</td> <td>76.842711</td> <td>$637.00	80.220055	66.366592	52.988247
12	12	Johnson High School	District	4761	$3,094,650.00</td> <td>80.966394</td> <td>77.072464</td> <td>$650.00	81.222432	66.057551	53.539172
13	13	Ford High School	District	2739	$1,763,916.00</td> <td>80.746258</td> <td>77.102592</td> <td>$644.00	79.299014	68.309602	54.289887
14	14	Thomas High School	Charter	1635	$1,043,130.00</td> <td>83.848930</td> <td>83.418349</td> <td>$638.00	97.308869	93.272171	90.948012
```
