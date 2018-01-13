<Type Name="DataFactoryListResponse" FullName="Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse">
  <TypeSignature Language="C#" Value="public class DataFactoryListResponse : Microsoft.Azure.AzureOperationResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataFactoryListResponse extends Microsoft.Azure.AzureOperationResponse" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class DataFactoryListResponse&#xA;Inherits AzureOperationResponse" />
  <TypeSignature Language="F#" Value="type DataFactoryListResponse = class&#xA;    inherit AzureOperationResponse" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.AzureOperationResponse</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d6cf2-101">一覧データ ファクトリ操作応答です。</span><span class="sxs-lookup"><span data-stu-id="d6cf2-101">The List data factories operation response.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataFactoryListResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d6cf2-102">DataFactoryListResponse クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d6cf2-102">Initializes a new instance of the DataFactoryListResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataFactoryListResponse (string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (nextLink As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse : string -&gt; Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse" Usage="new Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse nextLink" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nextLink">To be added.</param>
        <summary>
            <span data-ttu-id="d6cf2-103">必須の引数で DataFactoryListResponse クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d6cf2-103">Initializes a new instance of the DataFactoryListResponse class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataFactories">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactory&gt; DataFactories { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactory&gt; DataFactories" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse.DataFactories" />
      <MemberSignature Language="VB.NET" Value="Public Property DataFactories As IList(Of DataFactory)" />
      <MemberSignature Language="F#" Value="member this.DataFactories : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactory&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse.DataFactories" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactory&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d6cf2-104">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d6cf2-104">Optional.</span></span> <span data-ttu-id="d6cf2-105">すべてのデータ ファクトリ インスタンス リソース グループにします。</span><span class="sxs-lookup"><span data-stu-id="d6cf2-105">All the data factory instances in the resource group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextLink">
      <MemberSignature Language="C#" Value="public string NextLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse.NextLink" />
      <MemberSignature Language="VB.NET" Value="Public Property NextLink As String" />
      <MemberSignature Language="F#" Value="member this.NextLink : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse.NextLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d6cf2-106">必須。</span><span class="sxs-lookup"><span data-stu-id="d6cf2-106">Required.</span></span> <span data-ttu-id="d6cf2-107">結果の次のページへのリンク (url)。</span><span class="sxs-lookup"><span data-stu-id="d6cf2-107">The link (url) to the next page of results.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>