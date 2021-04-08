# Python-codes
in_list=[1, 2, 3, 4, 5]

def new_array(in_list):
    out_list = []

    for i, val in enumerate(in_list):
        org_list = in_list
        temp = org_list[i]
        org_list[i] = 1
        res = 1
        for x in org_list:
            result = res * x
        out_list.append(res)
        org_list[i] = temp
    return out_list

r=new_array(in_list)
print(r)
