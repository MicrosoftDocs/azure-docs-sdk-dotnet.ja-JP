<Type Name="ComputeNodeEndpointConfiguration" FullName="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration">
  <TypeSignature Language="C#" Value="public class ComputeNodeEndpointConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ComputeNodeEndpointConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class ComputeNodeEndpointConfiguration" />
  <TypeSignature Language="F#" Value="type ComputeNodeEndpointConfiguration = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            コンピューティング ノードのエンドポイント構成。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeNodeEndpointConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ComputeNodeEndpointConfiguration クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeNodeEndpointConfiguration (System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint&gt; inboundEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint&gt; inboundEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (inboundEndpoints As IList(Of InboundEndpoint))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration" Usage="new Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration inboundEndpoints" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="inboundEndpoints" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint&gt;" />
      </Parameters>
      <Docs>
        <param name="inboundEndpoints">コンピューティング ノード上でアクセス可能な受信エンドポイントの一覧。</param>
        <summary>
            ComputeNodeEndpointConfiguration クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InboundEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint&gt; InboundEndpoints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint&gt; InboundEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration.InboundEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Property InboundEndpoints As IList(Of InboundEndpoint)" />
      <MemberSignature Language="F#" Value="member this.InboundEndpoints : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration.InboundEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="inboundEndpoints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または計算ノード上でアクセス可能な受信エンドポイントのリストを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="computeNodeEndpointConfiguration.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>