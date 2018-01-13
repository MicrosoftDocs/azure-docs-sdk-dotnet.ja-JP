<Type Name="BatchSharedKeyCredentials" FullName="Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials">
  <TypeSignature Language="C#" Value="public class BatchSharedKeyCredentials : Microsoft.Azure.Batch.Auth.BatchCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchSharedKeyCredentials extends Microsoft.Azure.Batch.Auth.BatchCredentials" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchSharedKeyCredentials&#xA;Inherits BatchCredentials" />
  <TypeSignature Language="F#" Value="type BatchSharedKeyCredentials = class&#xA;    inherit BatchCredentials" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Auth.BatchCredentials</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Azure Batch アカウントのキーの資格情報を共有します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchSharedKeyCredentials (string baseUrl, string accountName, string keyValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string baseUrl, string accountName, string keyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUrl As String, accountName As String, keyValue As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials : string * string * string -&gt; Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials" Usage="new Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials (baseUrl, accountName, keyValue)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUrl" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="baseUrl">バッチ サービス エンドポイント。</param>
        <param name="accountName">Batch アカウントの名前。</param>
        <param name="keyValue">Base64 でエンコードされたアカウント アクセス キー。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials" />指定されたバッチ サービスのエンドポイント、アカウント名、およびアクセス キーを持つクラス。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountName">
      <MemberSignature Language="C#" Value="public string AccountName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials.AccountName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountName As String" />
      <MemberSignature Language="F#" Value="member this.AccountName : string" Usage="Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials.AccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Batch アカウント名を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>