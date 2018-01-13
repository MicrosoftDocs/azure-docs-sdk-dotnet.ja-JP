<Type Name="NodeAgentSku" FullName="Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku">
  <TypeSignature Language="C#" Value="public class NodeAgentSku" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NodeAgentSku extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeAgentSku" />
  <TypeSignature Language="F#" Value="type NodeAgentSku = class" />
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
            ノード エージェント SKU は、バッチ サービスによってサポートされます。
            </summary>
    <remarks>
            Batch ノード エージェントは、プール内の各ノード上で実行され、ノードと、バッチ サービスの間のコマンドとコントロール インターフェイスを提供するプログラムです。 オペレーティング システムに応じてさまざまなノード エージェントの実装 (SKU と呼ばれます) があります。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeAgentSku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku.#ctor" />
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
            NodeAgentSku クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeAgentSku (string id = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ImageReference&gt; verifiedImageReferences = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OSType&gt; osType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ImageReference&gt; verifiedImageReferences, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OSType&gt; osType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ImageReference},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.OSType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional verifiedImageReferences As IList(Of ImageReference) = null, Optional osType As Nullable(Of OSType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ImageReference&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OSType&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku" Usage="new Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku (id, verifiedImageReferences, osType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="verifiedImageReferences" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ImageReference&gt;" />
        <Parameter Name="osType" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OSType&gt;" />
      </Parameters>
      <Docs>
        <param name="id">ノード エージェント SKU の ID。</param>
        <param name="verifiedImageReferences">このノード エージェント SKU との互換性が確認済みの Azure Marketplace イメージの一覧。</param>
        <param name="osType">ノード エージェント SKU と互換性のオペレーティング システム (Windows または Linux) の型。</param>
        <summary>
            NodeAgentSku クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはノード エージェント SKU の ID を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OSType&gt; OsType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OSType&gt; OsType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku.OsType" />
      <MemberSignature Language="VB.NET" Value="Public Property OsType As Nullable(Of OSType)" />
      <MemberSignature Language="F#" Value="member this.OsType : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OSType&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku.OsType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OSType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはノード エージェント SKU と互換性のあるオペレーティング システム (Windows または Linux) の種類を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            使用可能な値が含まれます: 'linux'、'windows'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifiedImageReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ImageReference&gt; VerifiedImageReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ImageReference&gt; VerifiedImageReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku.VerifiedImageReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property VerifiedImageReferences As IList(Of ImageReference)" />
      <MemberSignature Language="F#" Value="member this.VerifiedImageReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ImageReference&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku.VerifiedImageReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="verifiedImageReferences")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ImageReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこのノード エージェント SKU との互換性が確認済みの Azure Marketplace イメージの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このコレクションが完全ではありません (ノードのエージェントは、その他のイメージと互換性のある可能性があります)。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>