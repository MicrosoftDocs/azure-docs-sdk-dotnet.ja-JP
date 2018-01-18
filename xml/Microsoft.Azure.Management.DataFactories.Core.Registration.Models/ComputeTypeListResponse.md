<Type Name="ComputeTypeListResponse" FullName="Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse">
  <TypeSignature Language="C#" Value="public class ComputeTypeListResponse : Microsoft.Azure.AzureOperationResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ComputeTypeListResponse extends Microsoft.Azure.AzureOperationResponse" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class ComputeTypeListResponse&#xA;Inherits AzureOperationResponse" />
  <TypeSignature Language="F#" Value="type ComputeTypeListResponse = class&#xA;    inherit AzureOperationResponse" />
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
            <span data-ttu-id="c5a80-101">リスト ComputeType 操作の応答。</span><span class="sxs-lookup"><span data-stu-id="c5a80-101">The List ComputeType operation response.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeTypeListResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c5a80-102">ComputeTypeListResponse クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c5a80-102">Initializes a new instance of the ComputeTypeListResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeTypeListResponse (string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (nextLink As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse : string -&gt; Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse" Usage="new Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse nextLink" />
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
            <span data-ttu-id="c5a80-103">必須の引数で ComputeTypeListResponse クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c5a80-103">Initializes a new instance of the ComputeTypeListResponse class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputeTypes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeType&gt; ComputeTypes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeType&gt; ComputeTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse.ComputeTypes" />
      <MemberSignature Language="VB.NET" Value="Public Property ComputeTypes As IList(Of ComputeType)" />
      <MemberSignature Language="F#" Value="member this.ComputeTypes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeType&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse.ComputeTypes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c5a80-104">省略可能。</span><span class="sxs-lookup"><span data-stu-id="c5a80-104">Optional.</span></span> <span data-ttu-id="c5a80-105">ComputeType 定義をすべて特定 RegistrationScope です。</span><span class="sxs-lookup"><span data-stu-id="c5a80-105">All the ComputeType definitions for a particular RegistrationScope.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextLink">
      <MemberSignature Language="C#" Value="public string NextLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse.NextLink" />
      <MemberSignature Language="VB.NET" Value="Public Property NextLink As String" />
      <MemberSignature Language="F#" Value="member this.NextLink : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.Registration.Models.ComputeTypeListResponse.NextLink" />
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
            <span data-ttu-id="c5a80-106">必須。</span><span class="sxs-lookup"><span data-stu-id="c5a80-106">Required.</span></span> <span data-ttu-id="c5a80-107">結果の次のページへのリンク (url)。</span><span class="sxs-lookup"><span data-stu-id="c5a80-107">The link (url) to the next page of results.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>