<Type Name="DownloadDirectoryOptions" FullName="Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions">
  <TypeSignature Language="C#" Value="public sealed class DownloadDirectoryOptions : Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DownloadDirectoryOptions extends Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DownloadDirectoryOptions&#xA;Inherits DirectoryOptions" />
  <TypeSignature Language="F#" Value="type DownloadDirectoryOptions = class&#xA;    inherit DirectoryOptions" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
    <AssemblyVersion>0.5.3.0</AssemblyVersion>
    <AssemblyVersion>0.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ダウンロード ディレクトリ操作で指定できるオプションのセットを表します
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DownloadDirectoryOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delimiter">
      <MemberSignature Language="C#" Value="public char Delimiter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance char Delimiter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions.Delimiter" />
      <MemberSignature Language="VB.NET" Value="Public Property Delimiter As Char" />
      <MemberSignature Language="F#" Value="member this.Delimiter : char with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions.Delimiter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Char</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または仮想ディレクトリの blob 名を区切るために使用する区切り文字を示す文字を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableContentMD5Validation">
      <MemberSignature Language="C#" Value="public bool DisableContentMD5Validation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool DisableContentMD5Validation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions.DisableContentMD5Validation" />
      <MemberSignature Language="VB.NET" Value="Public Property DisableContentMD5Validation As Boolean" />
      <MemberSignature Language="F#" Value="member this.DisableContentMD5Validation : bool with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions.DisableContentMD5Validation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコンテンツの MD5 またはソース オブジェクトからデータを読み込んでいないときに検証するかどうかを示すフラグを設定します。
            かどうか、コンテンツのソース オブジェクトは true に設定 MD5 検証されます。それ以外の場合、ソース オブジェクトのコンテンツ MD5 は検証されません。
            指定しない場合の既定値は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludeSnapshots">
      <MemberSignature Language="C#" Value="public bool IncludeSnapshots { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IncludeSnapshots" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions.IncludeSnapshots" />
      <MemberSignature Language="VB.NET" Value="Public Property IncludeSnapshots As Boolean" />
      <MemberSignature Language="F#" Value="member this.IncludeSnapshots : bool with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions.IncludeSnapshots" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure blob ストレージからダウンロードするときに、スナップショットを含めるかどうかを示すフラグを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            コピー元 blob のスナップショットが true の場合、このフラグが設定されている場合は、個別のファイルとしてコピー先にコピーされます。 "X.y"の形式でソース blob 名を指定するには、ここで 'x' は、ファイル名拡張子のない、'y' がファイル名拡張子は blob のスナップショットの対象ファイルの名前形式"x (%snapshot_time_stamp%).y"です。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>