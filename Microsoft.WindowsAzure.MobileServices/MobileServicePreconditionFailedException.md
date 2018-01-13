<Type Name="MobileServicePreconditionFailedException" FullName="Microsoft.WindowsAzure.MobileServices.MobileServicePreconditionFailedException">
  <TypeSignature Language="C#" Value="public class MobileServicePreconditionFailedException : Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileServicePreconditionFailedException extends Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.MobileServicePreconditionFailedException" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileServicePreconditionFailedException&#xA;Inherits MobileServiceInvalidOperationException" />
  <TypeSignature Language="F#" Value="type MobileServicePreconditionFailedException = class&#xA;    inherit MobileServiceInvalidOperationException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ' Precondition Failed' のステータス コードでの http 応答の詳細についてを説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServicePreconditionFailedException (Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException source, Newtonsoft.Json.Linq.JObject value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException source, class Newtonsoft.Json.Linq.JObject value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServicePreconditionFailedException.#ctor(Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException,Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (source As MobileServiceInvalidOperationException, value As JObject)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.MobileServicePreconditionFailedException : Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException * Newtonsoft.Json.Linq.JObject -&gt; Microsoft.WindowsAzure.MobileServices.MobileServicePreconditionFailedException" Usage="new Microsoft.WindowsAzure.MobileServices.MobileServicePreconditionFailedException (source, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException" />
        <Parameter Name="value" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="source">
            内部例外。
            </param>
        <param name="value">
            前提条件が失敗しました。 サーバーから現在のインスタンス。
            </param>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.MobileServices.MobileServicePreconditionFailedException" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>