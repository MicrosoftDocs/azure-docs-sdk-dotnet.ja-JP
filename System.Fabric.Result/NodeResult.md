<Type Name="NodeResult" FullName="System.Fabric.Result.NodeResult">
  <TypeSignature Language="C#" Value="public class NodeResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit NodeResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Result.NodeResult" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeResult" />
  <TypeSignature Language="F#" Value="type NodeResult = class" />
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
            結果オブジェクトのノードを返します。 
            </summary>
    <remarks>
            このクラスは、nodeName と nodeInstanceId を返します。 このクラスは、一部の RestartNode、StartNode、StopNode アクション結果構造体。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="NodeInstance">
      <MemberSignature Language="C#" Value="public System.Numerics.BigInteger NodeInstance { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Numerics.BigInteger NodeInstance" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.NodeResult.NodeInstance" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeInstance As BigInteger" />
      <MemberSignature Language="F#" Value="member this.NodeInstance : System.Numerics.BigInteger" Usage="System.Fabric.Result.NodeResult.NodeInstance" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Numerics.BigInteger</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ノード インスタンスの id を取得します。
            </summary>
        <value>ノード インスタンスの id です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.NodeResult.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Result.NodeResult.NodeName" />
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
            ノード名を取得します。
            </summary>
        <value>ノード名。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Result.NodeResult.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeResult.ToString " />
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
            ように文字列を返します:"NodeName: 文字列、ノード インスタンス: BigInteger"
            </summary>
        <returns>文字列</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>