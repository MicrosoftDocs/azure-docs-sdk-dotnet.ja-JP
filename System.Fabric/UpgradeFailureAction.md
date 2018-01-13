<Type Name="UpgradeFailureAction" FullName="System.Fabric.UpgradeFailureAction">
  <TypeSignature Language="C#" Value="public enum UpgradeFailureAction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed UpgradeFailureAction extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.UpgradeFailureAction" />
  <TypeSignature Language="VB.NET" Value="Public Enum UpgradeFailureAction" />
  <TypeSignature Language="F#" Value="type UpgradeFailureAction = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>Service Fabric アップグレードが失敗した場合に実行するアクションを列挙します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeFailureAction Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeFailureAction.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.UpgradeFailureAction.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeFailureAction</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>このアップグレードが有効ではないことを示します。 無効な型であるすべての Service Fabric 列挙体。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Manual">
      <MemberSignature Language="C#" Value="Manual" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeFailureAction Manual = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeFailureAction.Manual" />
      <MemberSignature Language="VB.NET" Value="Manual" />
      <MemberSignature Language="F#" Value="Manual = 2" Usage="System.Fabric.UpgradeFailureAction.Manual" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeFailureAction</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>手動の修復は、アップグレードが失敗した場合、管理者が実行する必要があることを示します。 Service Fabric は、次のアップグレード ドメインに自動的に続行できません。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Rollback">
      <MemberSignature Language="C#" Value="Rollback" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeFailureAction Rollback = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeFailureAction.Rollback" />
      <MemberSignature Language="VB.NET" Value="Rollback" />
      <MemberSignature Language="F#" Value="Rollback = 1" Usage="System.Fabric.UpgradeFailureAction.Rollback" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeFailureAction</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>アップグレードが失敗した場合に、アップグレードのロールバックを Service Fabric で実行することを示します。</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>