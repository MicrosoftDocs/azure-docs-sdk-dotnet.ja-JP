<Type Name="DiagnosticCondition" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition">
  <TypeSignature Language="C#" Value="public class DiagnosticCondition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DiagnosticCondition extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition" />
  <TypeSignature Language="VB.NET" Value="Public Class DiagnosticCondition" />
  <TypeSignature Language="F#" Value="type DiagnosticCondition = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f78ca-101">顧客の注意を立証リソース、またはに全体的なジョブに適用可能な条件です。</span><span class="sxs-lookup"><span data-stu-id="f78ca-101">Condition applicable to the resource, or to the job overall, that warrant customer attention.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DiagnosticCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f78ca-102">DiagnosticCondition クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f78ca-102">Initializes a new instance of the DiagnosticCondition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DiagnosticCondition (string since = null, string code = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string since, string code, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional since As String = null, Optional code As String = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition : string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition (since, code, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="since" Type="System.String" />
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="since"><span data-ttu-id="f78ca-103">条件の開始時の UTC タイムスタンプ。</span><span class="sxs-lookup"><span data-stu-id="f78ca-103">The UTC timestamp of when the condition started.</span></span> <span data-ttu-id="f78ca-104">ユーザーは、この時刻の周辺 ops ログで、対応するイベントを見つけることが必要があります。</span><span class="sxs-lookup"><span data-stu-id="f78ca-104">Customers should be able to find a corresponding event in the ops log around this time.</span></span></param>
        <param name="code"><span data-ttu-id="f78ca-105">不透明な診断コードです。</span><span class="sxs-lookup"><span data-stu-id="f78ca-105">The opaque diagnostic code.</span></span></param>
        <param name="message"><span data-ttu-id="f78ca-106">条件の詳細を説明する人間が判読できるメッセージ。</span><span class="sxs-lookup"><span data-stu-id="f78ca-106">The human-readable message describing the condition in detail.</span></span> <span data-ttu-id="f78ca-107">クライアント要求の Accept 言語でローカライズされます。</span><span class="sxs-lookup"><span data-stu-id="f78ca-107">Localized in the Accept-Language of the client request.</span></span></param>
        <summary>
            <span data-ttu-id="f78ca-108">DiagnosticCondition クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f78ca-108">Initializes a new instance of the DiagnosticCondition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition.Code" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="code")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f78ca-109">不透明な診断コードを取得します。</span><span class="sxs-lookup"><span data-stu-id="f78ca-109">Gets the opaque diagnostic code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f78ca-110">詳細の状態を示す、人間が判読できるメッセージを取得します。</span><span class="sxs-lookup"><span data-stu-id="f78ca-110">Gets the human-readable message describing the condition in detail.</span></span>
            <span data-ttu-id="f78ca-111">クライアント要求の Accept 言語でローカライズされます。</span><span class="sxs-lookup"><span data-stu-id="f78ca-111">Localized in the Accept-Language of the client request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Since">
      <MemberSignature Language="C#" Value="public string Since { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Since" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition.Since" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Since As String" />
      <MemberSignature Language="F#" Value="member this.Since : string" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition.Since" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="since")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f78ca-112">条件の開始時の UTC タイムスタンプを取得します。</span><span class="sxs-lookup"><span data-stu-id="f78ca-112">Gets the UTC timestamp of when the condition started.</span></span> <span data-ttu-id="f78ca-113">ユーザーは、この時刻の周辺 ops ログで、対応するイベントを見つけることが必要があります。</span><span class="sxs-lookup"><span data-stu-id="f78ca-113">Customers should be able to find a corresponding event in the ops log around this time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>