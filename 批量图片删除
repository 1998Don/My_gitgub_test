#批量图片删除
import os

def rename_im():
    add = '/Users/dingcong/Desktop'
    i=1
    for root,dirs,file in os.walk(add):
        for f in file:
            srcname = os.path.join(add,f)
            srcformat = srcname.split('/')[-1][:4]
            if srcformat == '屏幕快照':
                os.remove(srcname)
                i+=1

    print("图片名称批量删除完成!")
    print("图片总数为：",i-1)
    print("请您验收！")
    
if __name__ ==  '__main__':
    rename_im()
    
    
