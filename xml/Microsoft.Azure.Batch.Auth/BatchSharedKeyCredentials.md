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
            <span data-ttu-id="977ae-101">Azure Batch アカウントのキーの資格情報を共有します。</span><span class="sxs-lookup"><span data-stu-id="977ae-101">Shared key credentials for an Azure Batch account.</span></span>
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
        <param name="baseUrl"><span data-ttu-id="977ae-102">バッチ サービス エンドポイント。</span><span class="sxs-lookup"><span data-stu-id="977ae-102">The Batch service endpoint.</span></span></param>
        <param name="accountName"><span data-ttu-id="977ae-103">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="977ae-103">The name of the Batch account.</span></span></param>
        <param name="keyValue"><span data-ttu-id="977ae-104">Base64 でエンコードされたアカウント アクセス キー。</span><span class="sxs-lookup"><span data-stu-id="977ae-104">The Base64 encoded account access key.</span></span></param>
        <summary>
            <span data-ttu-id="977ae-105">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials" />指定されたバッチ サービスのエンドポイント、アカウント名、およびアクセス キーを持つクラス。</span><span class="sxs-lookup"><span data-stu-id="977ae-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials" /> class with the specified Batch service endpoint, account name, and access key.</span></span>
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
            <span data-ttu-id="977ae-106">Batch アカウント名を取得します。</span><span class="sxs-lookup"><span data-stu-id="977ae-106">Gets the Batch account name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>