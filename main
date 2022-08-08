 internal class Tema
    {
        private static Form formBase;
        public Tema(Form f){
          formBase = f;
          }

     

        public static List<Control> WhiteList = new List<Control>();
        public static List<Control> BlackList = new List<Control>();

        public static Color[] colors = { };


        private void Checar()
        {

            WhiteList.Clear();

            foreach (Control c in formBase.Controls) {
                foreach (Control b in BlackList) {
                    if (c != b) {
                        if (c == c as Label) WhiteList.Add((Label)c);
                        else if (c == c as Button) WhiteList.Add((Button)c);
                        else if (c == c as CheckBox) WhiteList.Add((CheckBox)c);
                        else if (c == c as TextBox) WhiteList.Add((TextBox)c);
                    }
                }
            }
        }

        public void iniciar(Form f)
        {
            if(formBase != null)
            {


            } 
        }
    }
