using System;
using System.Windows.Forms;

namespace WindowsFormsUygulamasi
{
    public partial class MainForm : Form
    {
        public MainForm()
        {
            InitializeComponent();
        }

        private void MainForm_Load(object sender, EventArgs e)
        {
            // Form yüklendiğinde yapılacak işlemler buraya yazılır
        }

        private void btnClickMe_Click(object sender, EventArgs e)
        {
            MessageBox.Show("Butona Tıklandı!");
        }
    }
}
