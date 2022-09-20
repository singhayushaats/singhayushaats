 int get(int i)
        {
            if(i<nextIndex)
            {
                return data[i];

            }
            else
            return -1;
        }
        void add(int i,int element)
        {
            if(i<nextIndex)
            {
                data[i]=element;

            }
            else if(i==nextIndex)
            {
                add(element);
            }
            else{
               return; 
            }
        }
        void print()
        {
            for(int i=0;i<nextIndex;i++)
            {
                cout<<data[i]<<endl;
            }
        }
