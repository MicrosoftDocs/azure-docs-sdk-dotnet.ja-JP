<Type Name="RepairTaskFlags" FullName="System.Fabric.Repair.RepairTaskFlags">
  <TypeSignature Language="C#" Value="public enum RepairTaskFlags" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed RepairTaskFlags extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Repair.RepairTaskFlags" />
  <TypeSignature Language="VB.NET" Value="Public Enum RepairTaskFlags" />
  <TypeSignature Language="F#" Value="type RepairTaskFlags = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>System.Flags</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>修復タスクに関する拡張状態情報を提供するフラグを定義します。</para>
      <para>この型は、Service Fabric プラットフォームをサポートしています。コードから直接使用するものではありません。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AbortRequested">
      <MemberSignature Language="C#" Value="AbortRequested" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskFlags AbortRequested = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskFlags.AbortRequested" />
      <MemberSignature Language="VB.NET" Value="AbortRequested" />
      <MemberSignature Language="F#" Value="AbortRequested = 2" Usage="System.Fabric.Repair.RepairTaskFlags.AbortRequested" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskFlags</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>ユーザーは、修復タスクの中止を要求しました。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="CancelRequested">
      <MemberSignature Language="C#" Value="CancelRequested" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskFlags CancelRequested = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskFlags.CancelRequested" />
      <MemberSignature Language="VB.NET" Value="CancelRequested" />
      <MemberSignature Language="F#" Value="CancelRequested = 1" Usage="System.Fabric.Repair.RepairTaskFlags.CancelRequested" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskFlags</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>ユーザーは、修復タスクのキャンセルを要求しました。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="ForcedApproval">
      <MemberSignature Language="C#" Value="ForcedApproval" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskFlags ForcedApproval = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskFlags.ForcedApproval" />
      <MemberSignature Language="VB.NET" Value="ForcedApproval" />
      <MemberSignature Language="F#" Value="ForcedApproval = 4" Usage="System.Fabric.Repair.RepairTaskFlags.ForcedApproval" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskFlags</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para>ユーザーが通常の安全性を保証せず実行される可能性がありますが、修復作業の承認を強制します。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskFlags None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskFlags.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="System.Fabric.Repair.RepairTaskFlags.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskFlags</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>フラグが指定されていません。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="ValidMask">
      <MemberSignature Language="C#" Value="ValidMask" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskFlags ValidMask = int32(7)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskFlags.ValidMask" />
      <MemberSignature Language="VB.NET" Value="ValidMask" />
      <MemberSignature Language="F#" Value="ValidMask = 7" Usage="System.Fabric.Repair.RepairTaskFlags.ValidMask" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskFlags</ReturnType>
      </ReturnValue>
      <MemberValue>7</MemberValue>
      <Docs>
        <summary>
          <para>すべての有効な修復作業フラグが含まれてマスクです。</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>