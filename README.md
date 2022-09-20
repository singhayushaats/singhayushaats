### Hi there 👋
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

<!--
**singhayushaats/singhayushaats** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
