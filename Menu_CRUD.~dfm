object Form1: TForm1
  Left = 275
  Top = 191
  Width = 1370
  Height = 726
  Caption = 'Form1'
  Color = clBtnFace
  Font.Charset = DEFAULT_CHARSET
  Font.Color = clWindowText
  Font.Height = -11
  Font.Name = 'MS Sans Serif'
  Font.Style = []
  OldCreateOrder = False
  PixelsPerInch = 96
  TextHeight = 13
  object Label1: TLabel
    Left = 24
    Top = 64
    Width = 62
    Height = 13
    Caption = 'Kode Barang'
  end
  object Label2: TLabel
    Left = 24
    Top = 96
    Width = 65
    Height = 13
    Caption = 'Nama Barang'
  end
  object Label3: TLabel
    Left = 24
    Top = 128
    Width = 66
    Height = 13
    Caption = 'Harga Barang'
  end
  object Label4: TLabel
    Left = 24
    Top = 168
    Width = 70
    Height = 13
    Caption = 'Jumlah Barang'
  end
  object Edit1: TEdit
    Left = 128
    Top = 64
    Width = 185
    Height = 21
    TabOrder = 0
  end
  object Edit2: TEdit
    Left = 128
    Top = 96
    Width = 185
    Height = 21
    TabOrder = 1
  end
  object Edit3: TEdit
    Left = 128
    Top = 128
    Width = 185
    Height = 21
    TabOrder = 2
  end
  object Edit4: TEdit
    Left = 128
    Top = 160
    Width = 185
    Height = 21
    TabOrder = 3
  end
  object Button1: TButton
    Left = 216
    Top = 208
    Width = 75
    Height = 25
    Caption = 'SAVE'
    TabOrder = 4
    OnClick = Button1Click
  end
  object Button2: TButton
    Left = 304
    Top = 208
    Width = 75
    Height = 25
    Caption = 'UPDATE'
    TabOrder = 5
    OnClick = Button2Click
  end
  object Button3: TButton
    Left = 392
    Top = 208
    Width = 75
    Height = 25
    Caption = 'DELETE'
    TabOrder = 6
    OnClick = Button3Click
  end
  object DBGrid1: TDBGrid
    Left = 96
    Top = 288
    Width = 537
    Height = 153
    DataSource = DataSource1
    TabOrder = 7
    TitleFont.Charset = DEFAULT_CHARSET
    TitleFont.Color = clWindowText
    TitleFont.Height = -11
    TitleFont.Name = 'MS Sans Serif'
    TitleFont.Style = []
  end
  object ZConnection1: TZConnection
    ControlsCodePage = cGET_ACP
    UTF8StringsAsWideField = False
    Properties.Strings = (
      'AutoEncodeStrings=ON')
    Connected = True
    HostName = 'localhost'
    Port = 0
    Database = 'penjualandb'
    User = 'root'
    Protocol = 'mysql'
    Left = 24
    Top = 8
  end
  object ZQuery1: TZQuery
    Connection = ZConnection1
    Active = True
    SQL.Strings = (
      'SELECT * FROM barang')
    Params = <>
    Left = 64
    Top = 8
  end
  object DataSource1: TDataSource
    DataSet = ZQuery1
    Left = 104
    Top = 8
  end
end
