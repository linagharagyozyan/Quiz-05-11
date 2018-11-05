#stack w/linked list
#define linkedlist
class linkedList:
    def __init__(self, data = None):
        self.data = data
        self.next = None  #do not have head and next, yet

class myStack:

    def __init__(self):
        self.head = None
        self.stack = []  #stack is empty, we can append there sth

    def setHead(self, newdata):
        self.head = linkedList(newdata)    #as we did not have head ,we set it, then head = newdata which has linked list type


#operations of stack/ isempty,push,pop,get

    def isEmpty(self):
        return self.stack == []

    def push(self, newdata):
        new_linkedList = linkedList(newdata) #create new list of newdata
        new_linkedList.next = self.head    #to push new data, first we need to not lose the connection of head with first data and new data, so we assign newlinkedlistnext to headnext, then assign headnext to newlinkedlist, then push new item
        self.head = new_linkedList
        self.stack.append(new_linkedList)


    def pop(self):
        if self.head is None:
            print "There is no object in linkedList"
        else:
            self.head = self.head.next
            return self.stack.pop()

    def get(self):
        for i in self.stack:
            print i.data


def main():
    linkedList = myStack()
    linkedList.pop()
    linkedList.get()
    linkedList.push(1)
    linkedList.push(2)
    linkedList.push(3)

main()
