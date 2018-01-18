<Type Name="PerfMonResponse" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.PerfMonResponse">
  <TypeSignature Language="C#" Value="public class PerfMonResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PerfMonResponse extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.PerfMonResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class PerfMonResponse" />
  <TypeSignature Language="F#" Value="type PerfMonResponse = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b183a-101">パフォーマンス モニター API の応答です。</span><span class="sxs-lookup"><span data-stu-id="b183a-101">Performance monitor API response.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PerfMonResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.PerfMonResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b183a-102">PerfMonResponse クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b183a-102">Initializes a new instance of the PerfMonResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PerfMonResponse (string code = null, string message = null, Microsoft.Azure.Management.AppService.Fluent.Models.PerfMonSet data = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, string message, class Microsoft.Azure.Management.AppService.Fluent.Models.PerfMonSet data) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.PerfMonResponse.#ctor(System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.PerfMonSet)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional code As String = null, Optional message As String = null, Optional data As PerfMonSet = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.PerfMonResponse : string * string * Microsoft.Azure.Management.AppService.Fluent.Models.PerfMonSet -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.PerfMonResponse" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.PerfMonResponse (code, message, data)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="data" Type="Microsoft.Azure.Management.AppService.Fluent.Models.PerfMonSet" />
      </Parameters>
      <Docs>
        <param name="code"><span data-ttu-id="b183a-103">応答コード。</span><span class="sxs-lookup"><span data-stu-id="b183a-103">The response code.</span></span></param>
        <param name="message"><span data-ttu-id="b183a-104">メッセージ。</span><span class="sxs-lookup"><span data-stu-id="b183a-104">The message.</span></span></param>
        <param name="data"><span data-ttu-id="b183a-105">パフォーマンス モニター カウンターです。</span><span class="sxs-lookup"><span data-stu-id="b183a-105">The performance monitor counters.</span></span></param>
        <summary>
            <span data-ttu-id="b183a-106">PerfMonResponse クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b183a-106">Initializes a new instance of the PerfMonResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.PerfMonResponse.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.PerfMonResponse.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="b183a-107">取得または応答コードを設定します。</span><span class="sxs-lookup"><span data-stu-id="b183a-107">Gets or sets the response code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Data">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.PerfMonSet Data { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.PerfMonSet Data" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.PerfMonResponse.Data" />
      <MemberSignature Language="VB.NET" Value="Public Property Data As PerfMonSet" />
      <MemberSignature Language="F#" Value="member this.Data : Microsoft.Azure.Management.AppService.Fluent.Models.PerfMonSet with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.PerfMonResponse.Data" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="data")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.PerfMonSet</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b183a-108">取得またはパフォーマンス モニター カウンターを設定します。</span><span class="sxs-lookup"><span data-stu-id="b183a-108">Gets or sets the performance monitor counters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.PerfMonResponse.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.PerfMonResponse.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="b183a-109">メッセージ取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="b183a-109">Gets or sets the message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>