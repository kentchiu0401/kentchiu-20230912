# kentchiu-20230912




totalnum = int(input('請輸入動物總數:'))
legs = int(input('請輸入動物腳數:'))
for chicken in range(0,totalnum+1):
    rabbit = totalnum - chicken
    if chicken*2 + rabbit*4 == legs:
        print('雞有'+str(chicken)+'隻，兔子有'+str(rabbit)+'隻')
        
if legs < totalnum*2 or legs > totalnum*4 or legs%2 !=0 :
    print('共有'+str(totalnum)+'隻動物，有'+str(legs)+'隻腳，無解')
    
