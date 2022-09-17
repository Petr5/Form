#include "mainwindow.h"
#include "ui_mainwindow.h"
#include <dialog.h>

MainWindow::MainWindow(QWidget *parent) :
    QMainWindow(parent),
    ui(new Ui::MainWindow)
{
    ui->setupUi(this);
}

MainWindow::~MainWindow()
{
    delete ui;
}

void MainWindow::on_checkBox_3_clicked(bool checked)
{

}

void MainWindow::on_pushButton_clicked()
{
//    Dialog dialog;
//    dialog.setModal(true);
//    dialog.exec();
    hide();
    Dialog* my_dialog = new Dialog(this);
    my_dialog->show();
}
