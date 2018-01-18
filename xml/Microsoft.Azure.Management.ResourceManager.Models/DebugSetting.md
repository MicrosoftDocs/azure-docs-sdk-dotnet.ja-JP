<Type Name="DebugSetting" FullName="Microsoft.Azure.Management.ResourceManager.Models.DebugSetting">
  <TypeSignature Language="C#" Value="public class DebugSetting" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DebugSetting extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.DebugSetting" />
  <TypeSignature Language="VB.NET" Value="Public Class DebugSetting" />
  <TypeSignature Language="F#" Value="type DebugSetting = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DebugSetting ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.DebugSetting.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9e5eb-101">DebugSetting クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9e5eb-101">Initializes a new instance of the DebugSetting class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DebugSetting (string detailLevel = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string detailLevel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.DebugSetting.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional detailLevel As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.DebugSetting : string -&gt; Microsoft.Azure.Management.ResourceManager.Models.DebugSetting" Usage="new Microsoft.Azure.Management.ResourceManager.Models.DebugSetting detailLevel" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="detailLevel" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="9e5eb-102">デバッグ ログ記録する情報の種類を指定します。</span><span class="sxs-lookup"><span data-stu-id="9e5eb-102">Specifies the type of information to log for debugging.</span></span> <span data-ttu-id="9e5eb-103">指定できる値は、none、コンマで区切られた requestContent responseContent、and、or 両方 requestContent responseContent です。</span><span class="sxs-lookup"><span data-stu-id="9e5eb-103">The permitted values are none, requestContent, responseContent, or both requestContent and responseContent separated by a comma.</span></span> <span data-ttu-id="9e5eb-104">既定値は none です。</span><span class="sxs-lookup"><span data-stu-id="9e5eb-104">The default is none.</span></span> <span data-ttu-id="9e5eb-105">この値を設定するにはとき、は、配置時に渡すことは、情報の種類を慎重に検討します。</span><span class="sxs-lookup"><span data-stu-id="9e5eb-105">When setting this value, carefully consider the type of information you are passing in during deployment.</span></span> <span data-ttu-id="9e5eb-106">要求または応答に関する情報をログ記録すると、デプロイ操作で取得される重要なデータを公開する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="9e5eb-106">By logging information about the request or response, you could potentially expose sensitive data that is retrieved through the deployment operations.</span></span></param>
        <summary>
            <span data-ttu-id="9e5eb-107">DebugSetting クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9e5eb-107">Initializes a new instance of the DebugSetting class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DetailLevel">
      <MemberSignature Language="C#" Value="public string DetailLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DetailLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DebugSetting.DetailLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property DetailLevel As String" />
      <MemberSignature Language="F#" Value="member this.DetailLevel : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DebugSetting.DetailLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="detailLevel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9e5eb-108">取得または設定は、デバッグ ログ記録する情報の種類を指定します。</span><span class="sxs-lookup"><span data-stu-id="9e5eb-108">Gets or sets specifies the type of information to log for debugging.</span></span> <span data-ttu-id="9e5eb-109">指定できる値は、none、コンマで区切られた requestContent responseContent、and、or 両方 requestContent responseContent です。</span><span class="sxs-lookup"><span data-stu-id="9e5eb-109">The permitted values are none, requestContent, responseContent, or both requestContent and responseContent separated by a comma.</span></span> <span data-ttu-id="9e5eb-110">既定値は none です。</span><span class="sxs-lookup"><span data-stu-id="9e5eb-110">The default is none.</span></span> <span data-ttu-id="9e5eb-111">この値を設定するにはとき、は、配置時に渡すことは、情報の種類を慎重に検討します。</span><span class="sxs-lookup"><span data-stu-id="9e5eb-111">When setting this value, carefully consider the type of information you are passing in during deployment.</span></span> <span data-ttu-id="9e5eb-112">要求または応答に関する情報をログ記録すると、デプロイ操作で取得される重要なデータを公開する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="9e5eb-112">By logging information about the request or response, you could potentially expose sensitive data that is retrieved through the deployment operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>