<Type Name="PipelineRunQueryResponse" FullName="Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryResponse">
  <TypeSignature Language="C#" Value="public class PipelineRunQueryResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PipelineRunQueryResponse extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class PipelineRunQueryResponse" />
  <TypeSignature Language="F#" Value="type PipelineRunQueryResponse = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4089e-101">一覧のパイプラインを実行します。</span><span class="sxs-lookup"><span data-stu-id="4089e-101">A list pipeline runs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PipelineRunQueryResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4089e-102">PipelineRunQueryResponse クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4089e-102">Initializes a new instance of the PipelineRunQueryResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PipelineRunQueryResponse (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRun&gt; value, string continuationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineRun&gt; value, string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryResponse.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.PipelineRun},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (value As IList(Of PipelineRun), Optional continuationToken As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryResponse : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRun&gt; * string -&gt; Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryResponse" Usage="new Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryResponse (value, continuationToken)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRun&gt;" />
        <Parameter Name="continuationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="4089e-103">パイプラインの一覧を実行します。</span><span class="sxs-lookup"><span data-stu-id="4089e-103">List of pipeline runs.</span></span></param>
        <param name="continuationToken"><span data-ttu-id="4089e-104">任意の残りの結果が存在する場合、null それ以外の場合、結果の次のページを取得するための継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="4089e-104">The continuation token for getting the next page of results, if any remaining results exist, null otherwise.</span></span></param>
        <summary>
            <span data-ttu-id="4089e-105">PipelineRunQueryResponse クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4089e-105">Initializes a new instance of the PipelineRunQueryResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public string ContinuationToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryResponse.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public Property ContinuationToken As String" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryResponse.ContinuationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="continuationToken")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4089e-106">取得または任意の残りの結果が存在する場合、null それ以外の場合、結果の次のページを取得するための継続トークンを設定します。</span><span class="sxs-lookup"><span data-stu-id="4089e-106">Gets or sets the continuation token for getting the next page of results, if any remaining results exist, null otherwise.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryResponse.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="pipelineRunQueryResponse.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4089e-107">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="4089e-107">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4089e-108">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4089e-108">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRun&gt; Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineRun&gt; Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryResponse.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As IList(Of PipelineRun)" />
      <MemberSignature Language="F#" Value="member this.Value : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRun&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryResponse.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRun&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4089e-109">取得またはパイプラインの実行の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="4089e-109">Gets or sets list of pipeline runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>