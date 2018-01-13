<Type Name="MoveSecondaryResult" FullName="System.Fabric.Result.MoveSecondaryResult">
  <TypeSignature Language="C#" Value="public class MoveSecondaryResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit MoveSecondaryResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Result.MoveSecondaryResult" />
  <TypeSignature Language="VB.NET" Value="Public Class MoveSecondaryResult" />
  <TypeSignature Language="F#" Value="type MoveSecondaryResult = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            セカンダリ レプリカの結果オブジェクトを表しますに移動します。
            </summary>
    <remarks>
            このクラスは、セカンダリ レプリカが現在移動、newSecondaryNodeName、SelectedReplica の移動先を選択したセカンダリ レプリカを表す SelectedPartition 情報の前に、currentSecondaryNodeName を返します。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="CurrentSecondaryNodeName">
      <MemberSignature Language="C#" Value="public string CurrentSecondaryNodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurrentSecondaryNodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.MoveSecondaryResult.CurrentSecondaryNodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentSecondaryNodeName As String" />
      <MemberSignature Language="F#" Value="member this.CurrentSecondaryNodeName : string" Usage="System.Fabric.Result.MoveSecondaryResult.CurrentSecondaryNodeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            対象のセカンダリ レプリカの現在のノード名を取得します。
            </summary>
        <value>対象のセカンダリ レプリカのノード名。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NewSecondaryNodeName">
      <MemberSignature Language="C#" Value="public string NewSecondaryNodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NewSecondaryNodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.MoveSecondaryResult.NewSecondaryNodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NewSecondaryNodeName As String" />
      <MemberSignature Language="F#" Value="member this.NewSecondaryNodeName : string" Usage="System.Fabric.Result.MoveSecondaryResult.NewSecondaryNodeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ここでセカンダリ レプリカの移動先とノード名を取得します。
            </summary>
        <value>ここで、ターゲット セカンダリ レプリカの移動先と、ノードの名前。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SelectedPartition">
      <MemberSignature Language="C#" Value="public System.Fabric.SelectedPartition SelectedPartition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SelectedPartition SelectedPartition" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.MoveSecondaryResult.SelectedPartition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SelectedPartition As SelectedPartition" />
      <MemberSignature Language="F#" Value="member this.SelectedPartition : System.Fabric.SelectedPartition" Usage="System.Fabric.Result.MoveSecondaryResult.SelectedPartition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SelectedPartition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            選択したパーティションを取得します。
            </summary>
        <value>SelectedPartition オブジェクトです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Result.MoveSecondaryResult.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="moveSecondaryResult.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            書式 CurrentSecondaryNodeName、NewSecondaryNodeName、および SelectedPartition 文字列に変換します。
            </summary>
        <returns>書式設定された文字列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>