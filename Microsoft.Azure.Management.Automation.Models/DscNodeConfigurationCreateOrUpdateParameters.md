<Type Name="DscNodeConfigurationCreateOrUpdateParameters" FullName="Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters">
  <TypeSignature Language="C#" Value="public class DscNodeConfigurationCreateOrUpdateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DscNodeConfigurationCreateOrUpdateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class DscNodeConfigurationCreateOrUpdateParameters" />
  <TypeSignature Language="F#" Value="type DscNodeConfigurationCreateOrUpdateParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0f3b3-101">作成または更新 ノードの構成操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="0f3b3-101">The parameters supplied to the create or update node configuration operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DscNodeConfigurationCreateOrUpdateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0f3b3-102">DscNodeConfigurationCreateOrUpdateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0f3b3-102">Initializes a new instance of the DscNodeConfigurationCreateOrUpdateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DscNodeConfigurationCreateOrUpdateParameters (Microsoft.Azure.Management.Automation.Models.ContentSource source, string name, Microsoft.Azure.Management.Automation.Models.DscConfigurationAssociationProperty configuration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Automation.Models.ContentSource source, string name, class Microsoft.Azure.Management.Automation.Models.DscConfigurationAssociationProperty configuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters.#ctor(Microsoft.Azure.Management.Automation.Models.ContentSource,System.String,Microsoft.Azure.Management.Automation.Models.DscConfigurationAssociationProperty)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (source As ContentSource, name As String, configuration As DscConfigurationAssociationProperty)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters : Microsoft.Azure.Management.Automation.Models.ContentSource * string * Microsoft.Azure.Management.Automation.Models.DscConfigurationAssociationProperty -&gt; Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters" Usage="new Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters (source, name, configuration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.Azure.Management.Automation.Models.ContentSource" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="configuration" Type="Microsoft.Azure.Management.Automation.Models.DscConfigurationAssociationProperty" />
      </Parameters>
      <Docs>
        <param name="source">To be added.</param>
        <param name="name">To be added.</param>
        <param name="configuration">To be added.</param>
        <summary>
            <span data-ttu-id="0f3b3-103">必須の引数で DscNodeConfigurationCreateOrUpdateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0f3b3-103">Initializes a new instance of the DscNodeConfigurationCreateOrUpdateParameters class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Configuration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.Models.DscConfigurationAssociationProperty Configuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.Models.DscConfigurationAssociationProperty Configuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters.Configuration" />
      <MemberSignature Language="VB.NET" Value="Public Property Configuration As DscConfigurationAssociationProperty" />
      <MemberSignature Language="F#" Value="member this.Configuration : Microsoft.Azure.Management.Automation.Models.DscConfigurationAssociationProperty with get, set" Usage="Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters.Configuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscConfigurationAssociationProperty</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0f3b3-104">必須。</span><span class="sxs-lookup"><span data-stu-id="0f3b3-104">Required.</span></span> <span data-ttu-id="0f3b3-105">取得またはノードの構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="0f3b3-105">Gets or sets the configuration of the node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncrementNodeConfigurationBuild">
      <MemberSignature Language="C#" Value="public bool IncrementNodeConfigurationBuild { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IncrementNodeConfigurationBuild" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters.IncrementNodeConfigurationBuild" />
      <MemberSignature Language="VB.NET" Value="Public Property IncrementNodeConfigurationBuild As Boolean" />
      <MemberSignature Language="F#" Value="member this.IncrementNodeConfigurationBuild : bool with get, set" Usage="Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters.IncrementNodeConfigurationBuild" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0f3b3-106">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0f3b3-106">Optional.</span></span> <span data-ttu-id="0f3b3-107">場合に、新しいビルドの設定を取得または NodeConfiguration のバージョンが必要です。</span><span class="sxs-lookup"><span data-stu-id="0f3b3-107">Gets or sets the if a new build version of NodeConfiguration is required.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0f3b3-108">必須。</span><span class="sxs-lookup"><span data-stu-id="0f3b3-108">Required.</span></span> <span data-ttu-id="0f3b3-109">取得またはパラメーターの型を設定します。</span><span class="sxs-lookup"><span data-stu-id="0f3b3-109">Gets or sets the type of the parameter.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.Models.ContentSource Source { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.Models.ContentSource Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters.Source" />
      <MemberSignature Language="VB.NET" Value="Public Property Source As ContentSource" />
      <MemberSignature Language="F#" Value="member this.Source : Microsoft.Azure.Management.Automation.Models.ContentSource with get, set" Usage="Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters.Source" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ContentSource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0f3b3-110">必須。</span><span class="sxs-lookup"><span data-stu-id="0f3b3-110">Required.</span></span> <span data-ttu-id="0f3b3-111">ソース取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="0f3b3-111">Gets or sets the source.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>