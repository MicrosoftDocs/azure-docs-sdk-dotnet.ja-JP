<Type Name="StorageProgress" FullName="Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress">
  <TypeSignature Language="C#" Value="public sealed class StorageProgress" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StorageProgress extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StorageProgress" />
  <TypeSignature Language="F#" Value="type StorageProgress = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            進行状況データに関する情報を単一の操作で両方の要求と応答のストリームの転送を保持します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageProgress (long bytesTransferred);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 bytesTransferred) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress.#ctor(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (bytesTransferred As Long)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress : int64 -&gt; Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" Usage="new Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress bytesTransferred" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="bytesTransferred" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="bytesTransferred">報告される進行状況の値。</param>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> オブジェクトを作成します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BytesTransferred">
      <MemberSignature Language="C#" Value="public long BytesTransferred { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 BytesTransferred" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress.BytesTransferred" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BytesTransferred As Long" />
      <MemberSignature Language="F#" Value="member this.BytesTransferred : int64" Usage="Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress.BytesTransferred" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            要求のデータ転送のバイト単位で進行中です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>