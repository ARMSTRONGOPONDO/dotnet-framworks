# dotnet-framworks
namespace WinFormsApp1
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void label1_Click(object sender, EventArgs e)
        {

        }

        private void Form1_Load(object sender, EventArgs e)
        {

        }

        private void label3_Click(object sender, EventArgs e)
        {

        }

        private void button1_Click(object sender, EventArgs e)
        {
            double maths, sciance, english, total, average;
            string grade;

            maths = int.Parse(txtm.Text);
            sciance = int.Parse(txts.Text);
            english = int.Parse(txte.Text);

            total = maths + sciance + english;

            txtt.Text = total.ToString();

            average = total /3;

            txta.Text=average.ToString();

            if (average > =75)
            {
                grade = "A";
            }
            if (average > = 65)
            {
                grade = "B";
            }




        }

        private void textBox1_TextChanged(object sender, EventArgs e)
        {

        }

        private void textBox2_TextChanged(object sender, EventArgs e)
        {

        }
    }
}
