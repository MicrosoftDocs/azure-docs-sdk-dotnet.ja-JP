<Type Name="DscCompilationJobCreateProperties" FullName="Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateProperties">
  <TypeSignature Language="C#" Value="public class DscCompilationJobCreateProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DscCompilationJobCreateProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class DscCompilationJobCreateProperties" />
  <TypeSignature Language="F#" Value="type DscCompilationJobCreateProperties = class" />
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
            <span data-ttu-id="dfb58-101">コンパイル ジョブの作成処理に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="dfb58-101">The parameters supplied to the create compilation job operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DscCompilationJobCreateProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dfb58-102">DscCompilationJobCreateProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="dfb58-102">Initializes a new instance of the DscCompilationJobCreateProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DscCompilationJobCreateProperties (Microsoft.Azure.Management.Automation.Models.DscConfigurationAssociationProperty configuration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Automation.Models.DscConfigurationAssociationProperty configuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateProperties.#ctor(Microsoft.Azure.Management.Automation.Models.DscConfigurationAssociationProperty)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (configuration As DscConfigurationAssociationProperty)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateProperties : Microsoft.Azure.Management.Automation.Models.DscConfigurationAssociationProperty -&gt; Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateProperties" Usage="new Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateProperties configuration" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="configuration" Type="Microsoft.Azure.Management.Automation.Models.DscConfigurationAssociationProperty" />
      </Parameters>
      <Docs>
        <param name="configuration">To be added.</param>
        <summary>
            <span data-ttu-id="dfb58-103">必須の引数で DscCompilationJobCreateProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="dfb58-103">Initializes a new instance of the DscCompilationJobCreateProperties class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Configuration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.Models.DscConfigurationAssociationProperty Configuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.Models.DscConfigurationAssociationProperty Configuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateProperties.Configuration" />
      <MemberSignature Language="VB.NET" Value="Public Property Configuration As DscConfigurationAssociationProperty" />
      <MemberSignature Language="F#" Value="member this.Configuration : Microsoft.Azure.Management.Automation.Models.DscConfigurationAssociationProperty with get, set" Usage="Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateProperties.Configuration" />
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
            <span data-ttu-id="dfb58-104">必須。</span><span class="sxs-lookup"><span data-stu-id="dfb58-104">Required.</span></span> <span data-ttu-id="dfb58-105">取得または設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="dfb58-105">Gets or sets the configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncrementNodeConfigurationBuild">
      <MemberSignature Language="C#" Value="public bool IncrementNodeConfigurationBuild { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IncrementNodeConfigurationBuild" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateProperties.IncrementNodeConfigurationBuild" />
      <MemberSignature Language="VB.NET" Value="Public Property IncrementNodeConfigurationBuild As Boolean" />
      <MemberSignature Language="F#" Value="member this.IncrementNodeConfigurationBuild : bool with get, set" Usage="Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateProperties.IncrementNodeConfigurationBuild" />
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
            <span data-ttu-id="dfb58-106">省略可能。</span><span class="sxs-lookup"><span data-stu-id="dfb58-106">Optional.</span></span> <span data-ttu-id="dfb58-107">場合に、新しいビルドの設定を取得または NodeConfiguration のバージョンが必要です。</span><span class="sxs-lookup"><span data-stu-id="dfb58-107">Gets or sets the if a new build version of NodeConfiguration is required.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateProperties.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateProperties.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dfb58-108">省略可能。</span><span class="sxs-lookup"><span data-stu-id="dfb58-108">Optional.</span></span> <span data-ttu-id="dfb58-109">取得または、ジョブのパラメーターを設定します。</span><span class="sxs-lookup"><span data-stu-id="dfb58-109">Gets or sets the parameters of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>