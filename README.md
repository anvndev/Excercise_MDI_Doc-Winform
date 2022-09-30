# Excercise_.Net_MDI-main
<br> Winform </br>
--------------------------------------
# Star

            if (!CheckExistForm("BT_ListBox"))
            {
                BT_ListBox frmListBox = new BT_ListBox();
                frmListBox.MdiParent = this;
                frmListBox.Show();
            }
            else
            {
                ActiveChildForm("BT_ListBox");
            }
