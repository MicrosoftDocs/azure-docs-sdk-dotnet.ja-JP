<Type Name="DownloadOptions" FullName="Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions">
  <TypeSignature Language="C#" Value="public sealed class DownloadOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DownloadOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DownloadOptions" />
  <TypeSignature Language="F#" Value="type DownloadOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
    <AssemblyVersion>0.5.3.0</AssemblyVersion>
    <AssemblyVersion>0.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ダウンロード操作に指定できるオプションのセットを表します
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DownloadOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions.#ctor" />
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
    <Member MemberName="DisableContentMD5Validation">
      <MemberSignature Language="C#" Value="public bool DisableContentMD5Validation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool DisableContentMD5Validation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions.DisableContentMD5Validation" />
      <MemberSignature Language="VB.NET" Value="Public Property DisableContentMD5Validation As Boolean" />
      <MemberSignature Language="F#" Value="member this.DisableContentMD5Validation : bool with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions.DisableContentMD5Validation" />
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
    <Member MemberName="SourceAccessCondition">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.AccessCondition SourceAccessCondition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.AccessCondition SourceAccessCondition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions.SourceAccessCondition" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceAccessCondition As AccessCondition" />
      <MemberSignature Language="F#" Value="member this.SourceAccessCondition : Microsoft.WindowsAzure.Storage.AccessCondition with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions.SourceAccessCondition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />ソース オブジェクトのアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>