<Type Name="HubListResponse" FullName="Microsoft.Azure.Management.DataFactories.Models.HubListResponse">
  <TypeSignature Language="C#" Value="public class HubListResponse : Microsoft.Azure.AzureOperationResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HubListResponse extends Microsoft.Azure.AzureOperationResponse" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.HubListResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class HubListResponse&#xA;Inherits AzureOperationResponse" />
  <TypeSignature Language="F#" Value="type HubListResponse = class&#xA;    inherit AzureOperationResponse" />
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
            <span data-ttu-id="0f6e6-101">リストのハブ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="0f6e6-101">The list hub operation response.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HubListResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.HubListResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0f6e6-102">HubListResponse クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0f6e6-102">Initializes a new instance of the HubListResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HubListResponse (string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.HubListResponse.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (nextLink As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.HubListResponse : string -&gt; Microsoft.Azure.Management.DataFactories.Models.HubListResponse" Usage="new Microsoft.Azure.Management.DataFactories.Models.HubListResponse nextLink" />
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
            <span data-ttu-id="0f6e6-103">必須の引数で HubListResponse クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0f6e6-103">Initializes a new instance of the HubListResponse class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Hubs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.Hub&gt; Hubs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactories.Models.Hub&gt; Hubs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HubListResponse.Hubs" />
      <MemberSignature Language="VB.NET" Value="Public Property Hubs As IList(Of Hub)" />
      <MemberSignature Language="F#" Value="member this.Hubs : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.Hub&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HubListResponse.Hubs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.Hub&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0f6e6-104">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0f6e6-104">Optional.</span></span> <span data-ttu-id="0f6e6-105">返されたハブ インスタンスの一覧です。</span><span class="sxs-lookup"><span data-stu-id="0f6e6-105">A list of the returned hub instances.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextLink">
      <MemberSignature Language="C#" Value="public string NextLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HubListResponse.NextLink" />
      <MemberSignature Language="VB.NET" Value="Public Property NextLink As String" />
      <MemberSignature Language="F#" Value="member this.NextLink : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HubListResponse.NextLink" />
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
            <span data-ttu-id="0f6e6-106">必須。</span><span class="sxs-lookup"><span data-stu-id="0f6e6-106">Required.</span></span> <span data-ttu-id="0f6e6-107">結果の次のページへのリンク (url)。</span><span class="sxs-lookup"><span data-stu-id="0f6e6-107">The link (url) to the next page of results.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>