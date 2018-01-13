<Type Name="NodeImpactLevel" FullName="System.Fabric.Repair.NodeImpactLevel">
  <TypeSignature Language="C#" Value="public enum NodeImpactLevel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed NodeImpactLevel extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Repair.NodeImpactLevel" />
  <TypeSignature Language="VB.NET" Value="Public Enum NodeImpactLevel" />
  <TypeSignature Language="F#" Value="type NodeImpactLevel = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>効果的な影響を列挙して、特定のノードで、修復が必要です。</para>
      <para>この型は、Service Fabric プラットフォームをサポートしています。コードから直接使用するものではありません。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.NodeImpactLevel Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.NodeImpactLevel.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.Repair.NodeImpactLevel.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.NodeImpactLevel</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>ノードへの影響のレベルが有効ではないことを示します。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.NodeImpactLevel None = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.NodeImpactLevel.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 1" Usage="System.Fabric.Repair.NodeImpactLevel.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.NodeImpactLevel</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>影響が必要ないことを示します。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="RemoveData">
      <MemberSignature Language="C#" Value="RemoveData" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.NodeImpactLevel RemoveData = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.NodeImpactLevel.RemoveData" />
      <MemberSignature Language="VB.NET" Value="RemoveData" />
      <MemberSignature Language="F#" Value="RemoveData = 3" Usage="System.Fabric.Repair.NodeImpactLevel.RemoveData" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.NodeImpactLevel</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>ノードが停止するには予測されることを示すし、すべての再起動の前の永続化された状態を失う可能性があります。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="RemoveNode">
      <MemberSignature Language="C#" Value="RemoveNode" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.NodeImpactLevel RemoveNode = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.NodeImpactLevel.RemoveNode" />
      <MemberSignature Language="VB.NET" Value="RemoveNode" />
      <MemberSignature Language="F#" Value="RemoveNode = 4" Usage="System.Fabric.Repair.NodeImpactLevel.RemoveNode" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.NodeImpactLevel</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para>ノードがクラスターから削除することを示します。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Restart">
      <MemberSignature Language="C#" Value="Restart" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.NodeImpactLevel Restart = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.NodeImpactLevel.Restart" />
      <MemberSignature Language="VB.NET" Value="Restart" />
      <MemberSignature Language="F#" Value="Restart = 2" Usage="System.Fabric.Repair.NodeImpactLevel.Restart" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.NodeImpactLevel</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>ノードが停止し、最終的に再起動する必要のあることを示します。</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>