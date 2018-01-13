<Type Name="SystemNodeRepairAction" FullName="System.Fabric.Repair.SystemNodeRepairAction">
  <TypeSignature Language="C#" Value="public enum SystemNodeRepairAction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed SystemNodeRepairAction extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Repair.SystemNodeRepairAction" />
  <TypeSignature Language="VB.NET" Value="Public Enum SystemNodeRepairAction" />
  <TypeSignature Language="F#" Value="type SystemNodeRepairAction = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>システムが組み込みの実行子を持っているノードの修復アクションを指定します。</para>
      <para>この型は、Service Fabric プラットフォームをサポートしています。コードから直接使用するものではありません。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FullReimage">
      <MemberSignature Language="C#" Value="FullReimage" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.SystemNodeRepairAction FullReimage = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.SystemNodeRepairAction.FullReimage" />
      <MemberSignature Language="VB.NET" Value="FullReimage" />
      <MemberSignature Language="F#" Value="FullReimage = 2" Usage="System.Fabric.Repair.SystemNodeRepairAction.FullReimage" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.SystemNodeRepairAction</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>ノードに格納されているすべてのデータは破棄、ターゲット ノードのすべてのディスク ボリュームを個です。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Reboot">
      <MemberSignature Language="C#" Value="Reboot" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.SystemNodeRepairAction Reboot = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.SystemNodeRepairAction.Reboot" />
      <MemberSignature Language="VB.NET" Value="Reboot" />
      <MemberSignature Language="F#" Value="Reboot = 0" Usage="System.Fabric.Repair.SystemNodeRepairAction.Reboot" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.SystemNodeRepairAction</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>ターゲット ノードの OS を再起動します。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="ReimageOS">
      <MemberSignature Language="C#" Value="ReimageOS" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.SystemNodeRepairAction ReimageOS = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.SystemNodeRepairAction.ReimageOS" />
      <MemberSignature Language="VB.NET" Value="ReimageOS" />
      <MemberSignature Language="F#" Value="ReimageOS = 1" Usage="System.Fabric.Repair.SystemNodeRepairAction.ReimageOS" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.SystemNodeRepairAction</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>ターゲット ノードの OS ボリュームを個です。</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>