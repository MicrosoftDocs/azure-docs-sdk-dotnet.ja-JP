<Type Name="NodeAgentSku" FullName="Microsoft.Azure.Batch.NodeAgentSku">
  <TypeSignature Language="C#" Value="public class NodeAgentSku" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NodeAgentSku extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.NodeAgentSku" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeAgentSku" />
  <TypeSignature Language="F#" Value="type NodeAgentSku = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            ノード エージェント SKU は、バッチ サービスによってサポートされます。 Batch ノード エージェントは、プール内の各ノード上で実行され、ノードと、バッチ サービスの間のコマンドとコントロール インターフェイスを提供するプログラムです。 オペレーティング システムに応じてさまざまなノード エージェントの実装 (SKU と呼ばれます) があります。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NodeAgentSku.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Batch.NodeAgentSku.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ノード エージェント SKU の id を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.OSType&gt; OSType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.OSType&gt; OSType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NodeAgentSku.OSType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSType As Nullable(Of OSType)" />
      <MemberSignature Language="F#" Value="member this.OSType : Nullable&lt;Microsoft.Azure.Batch.Common.OSType&gt;" Usage="Microsoft.Azure.Batch.NodeAgentSku.OSType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.OSType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ノード エージェント SKU と互換性のあるオペレーティング システムの種類を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifiedImageReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.ImageReference&gt; VerifiedImageReferences { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.ImageReference&gt; VerifiedImageReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NodeAgentSku.VerifiedImageReferences" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VerifiedImageReferences As IReadOnlyList(Of ImageReference)" />
      <MemberSignature Language="F#" Value="member this.VerifiedImageReferences : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.ImageReference&gt;" Usage="Microsoft.Azure.Batch.NodeAgentSku.VerifiedImageReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.ImageReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このノード エージェント SKU との互換性が確認済みの Azure Marketplace イメージの一覧を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このコレクションが完全ではありません (ノードのエージェントは、その他のイメージと互換性のある可能性があります)。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>