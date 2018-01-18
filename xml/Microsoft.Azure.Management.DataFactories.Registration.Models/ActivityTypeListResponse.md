<Type Name="ActivityTypeListResponse" FullName="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse">
  <TypeSignature Language="C#" Value="public class ActivityTypeListResponse : Microsoft.Azure.AzureOperationResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActivityTypeListResponse extends Microsoft.Azure.AzureOperationResponse" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class ActivityTypeListResponse&#xA;Inherits AzureOperationResponse" />
  <TypeSignature Language="F#" Value="type ActivityTypeListResponse = class&#xA;    inherit AzureOperationResponse" />
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
            <span data-ttu-id="e2886-101">リスト ActivityType 操作の応答。</span><span class="sxs-lookup"><span data-stu-id="e2886-101">The List ActivityType operation response.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActivityTypeListResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e2886-102">ActivityTypeListResponse クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e2886-102">Initializes a new instance of the ActivityTypeListResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActivityTypeListResponse (string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (nextLink As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse : string -&gt; Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse" Usage="new Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse nextLink" />
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
            <span data-ttu-id="e2886-103">必須の引数で ActivityTypeListResponse クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e2886-103">Initializes a new instance of the ActivityTypeListResponse class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivityTypes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityType&gt; ActivityTypes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityType&gt; ActivityTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse.ActivityTypes" />
      <MemberSignature Language="VB.NET" Value="Public Property ActivityTypes As IList(Of ActivityType)" />
      <MemberSignature Language="F#" Value="member this.ActivityTypes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityType&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse.ActivityTypes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e2886-104">省略可能。</span><span class="sxs-lookup"><span data-stu-id="e2886-104">Optional.</span></span> <span data-ttu-id="e2886-105">ActivityType 定義をすべて特定 RegistrationScope です。</span><span class="sxs-lookup"><span data-stu-id="e2886-105">All the ActivityType definitions for a particular RegistrationScope.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextLink">
      <MemberSignature Language="C#" Value="public string NextLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse.NextLink" />
      <MemberSignature Language="VB.NET" Value="Public Property NextLink As String" />
      <MemberSignature Language="F#" Value="member this.NextLink : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse.NextLink" />
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
            <span data-ttu-id="e2886-106">必須。</span><span class="sxs-lookup"><span data-stu-id="e2886-106">Required.</span></span> <span data-ttu-id="e2886-107">結果の次のページへのリンク (url)。</span><span class="sxs-lookup"><span data-stu-id="e2886-107">The link (url) to the next page of results.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>