<Type Name="QueryTroubleshootingParameters" FullName="Microsoft.Azure.Management.Network.Fluent.Models.QueryTroubleshootingParameters">
  <TypeSignature Language="C#" Value="public class QueryTroubleshootingParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit QueryTroubleshootingParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.QueryTroubleshootingParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class QueryTroubleshootingParameters" />
  <TypeSignature Language="F#" Value="type QueryTroubleshootingParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="11a66-101">クエリのトラブルシューティングの結果にリソースを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="11a66-101">Parameters that define the resource to query the troubleshooting result.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueryTroubleshootingParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.QueryTroubleshootingParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="11a66-102">QueryTroubleshootingParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="11a66-102">Initializes a new instance of the QueryTroubleshootingParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueryTroubleshootingParameters (string targetResourceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string targetResourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.QueryTroubleshootingParameters.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (targetResourceId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.QueryTroubleshootingParameters : string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.QueryTroubleshootingParameters" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.QueryTroubleshootingParameters targetResourceId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="targetResourceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="targetResourceId"><span data-ttu-id="11a66-103">クエリのトラブルシューティングの結果をターゲット リソース ID です。</span><span class="sxs-lookup"><span data-stu-id="11a66-103">The target resource ID to query the troubleshooting result.</span></span></param>
        <summary>
            <span data-ttu-id="11a66-104">QueryTroubleshootingParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="11a66-104">Initializes a new instance of the QueryTroubleshootingParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResourceId">
      <MemberSignature Language="C#" Value="public string TargetResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.QueryTroubleshootingParameters.TargetResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetResourceId As String" />
      <MemberSignature Language="F#" Value="member this.TargetResourceId : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.QueryTroubleshootingParameters.TargetResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="11a66-105">取得またはクエリのトラブルシューティングの結果をターゲット リソース ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="11a66-105">Gets or sets the target resource ID to query the troubleshooting result.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.QueryTroubleshootingParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="queryTroubleshootingParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="11a66-106">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="11a66-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="11a66-107">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11a66-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>