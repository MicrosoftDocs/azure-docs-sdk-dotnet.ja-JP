<Type Name="AzureBatchLinkedService" FullName="Microsoft.Azure.Management.DataFactories.Models.AzureBatchLinkedService">
  <TypeSignature Language="C#" Value="public class AzureBatchLinkedService : Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureBatchLinkedService extends Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.AzureBatchLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureBatchLinkedService&#xA;Inherits LinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type AzureBatchLinkedService = class&#xA;    inherit LinkedServiceTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("AzureBatch")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureBatchLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AzureBatchLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureBatchLinkedService (string accountName, string batchUri, string accessKey, string poolName, string linkedServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName, string batchUri, string accessKey, string poolName, string linkedServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AzureBatchLinkedService.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accountName As String, batchUri As String, accessKey As String, poolName As String, linkedServiceName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.AzureBatchLinkedService : string * string * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.AzureBatchLinkedService" Usage="new Microsoft.Azure.Management.DataFactories.Models.AzureBatchLinkedService (accountName, batchUri, accessKey, poolName, linkedServiceName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="batchUri" Type="System.String" />
        <Parameter Name="accessKey" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accountName">To be added.</param>
        <param name="batchUri">To be added.</param>
        <param name="accessKey">To be added.</param>
        <param name="poolName">To be added.</param>
        <param name="linkedServiceName">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessKey">
      <MemberSignature Language="C#" Value="public string AccessKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccessKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureBatchLinkedService.AccessKey" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessKey As String" />
      <MemberSignature Language="F#" Value="member this.AccessKey : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureBatchLinkedService.AccessKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8e674-101">必須。</span><span class="sxs-lookup"><span data-stu-id="8e674-101">Required.</span></span> <span data-ttu-id="8e674-102">Azure Batch アカウント アクセス キー。</span><span class="sxs-lookup"><span data-stu-id="8e674-102">The Azure Batch account access key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountName">
      <MemberSignature Language="C#" Value="public string AccountName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureBatchLinkedService.AccountName" />
      <MemberSignature Language="VB.NET" Value="Public Property AccountName As String" />
      <MemberSignature Language="F#" Value="member this.AccountName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureBatchLinkedService.AccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8e674-103">必須。</span><span class="sxs-lookup"><span data-stu-id="8e674-103">Required.</span></span> <span data-ttu-id="8e674-104">Azure Batch アカウント名。</span><span class="sxs-lookup"><span data-stu-id="8e674-104">The Azure Batch account name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchUri">
      <MemberSignature Language="C#" Value="public string BatchUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BatchUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureBatchLinkedService.BatchUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BatchUri As String" />
      <MemberSignature Language="F#" Value="member this.BatchUri : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureBatchLinkedService.BatchUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8e674-105">必須。</span><span class="sxs-lookup"><span data-stu-id="8e674-105">Required.</span></span> <span data-ttu-id="8e674-106">Azure Batch の URI。</span><span class="sxs-lookup"><span data-stu-id="8e674-106">The Azure Batch URI.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedServiceName">
      <MemberSignature Language="C#" Value="public string LinkedServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LinkedServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureBatchLinkedService.LinkedServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property LinkedServiceName As String" />
      <MemberSignature Language="F#" Value="member this.LinkedServiceName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureBatchLinkedService.LinkedServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8e674-107">必須。</span><span class="sxs-lookup"><span data-stu-id="8e674-107">Required.</span></span> <span data-ttu-id="8e674-108">Azure ストレージのリンクされたサービス名。</span><span class="sxs-lookup"><span data-stu-id="8e674-108">The azure storage linked service name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolName">
      <MemberSignature Language="C#" Value="public string PoolName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PoolName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureBatchLinkedService.PoolName" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolName As String" />
      <MemberSignature Language="F#" Value="member this.PoolName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureBatchLinkedService.PoolName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8e674-109">必須。</span><span class="sxs-lookup"><span data-stu-id="8e674-109">Required.</span></span> <span data-ttu-id="8e674-110">Azure Batch プールの名前。</span><span class="sxs-lookup"><span data-stu-id="8e674-110">The Azure Batch pool name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>