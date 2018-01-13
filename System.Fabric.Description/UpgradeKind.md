<Type Name="UpgradeKind" FullName="System.Fabric.Description.UpgradeKind">
  <TypeSignature Language="C#" Value="public enum UpgradeKind" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed UpgradeKind extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.UpgradeKind" />
  <TypeSignature Language="VB.NET" Value="Public Enum UpgradeKind" />
  <TypeSignature Language="F#" Value="type UpgradeKind = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>可能なアップグレードの種類を列挙します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.UpgradeKind Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.UpgradeKind.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.Description.UpgradeKind.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.UpgradeKind</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>これが、無効なアップグレードであることを示します。 すべての Service Fabric の列挙には、予約済みの「無効」メンバーがあります。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Rolling">
      <MemberSignature Language="C#" Value="Rolling" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.UpgradeKind Rolling = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.UpgradeKind.Rolling" />
      <MemberSignature Language="VB.NET" Value="Rolling" />
      <MemberSignature Language="F#" Value="Rolling = 1" Usage="System.Fabric.Description.UpgradeKind.Rolling" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.UpgradeKind</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>ローリング アップグレードであることを示します。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Rolling_ForceRestart">
      <MemberSignature Language="C#" Value="Rolling_ForceRestart" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.UpgradeKind Rolling_ForceRestart = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.UpgradeKind.Rolling_ForceRestart" />
      <MemberSignature Language="VB.NET" Value="Rolling_ForceRestart" />
      <MemberSignature Language="F#" Value="Rolling_ForceRestart = 2" Usage="System.Fabric.Description.UpgradeKind.Rolling_ForceRestart" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.UpgradeKind</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>これは、ローリング アップグレードは、サービス ホストが再起動ことを示します。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Rolling_NotificationOnly">
      <MemberSignature Language="C#" Value="Rolling_NotificationOnly" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.UpgradeKind Rolling_NotificationOnly = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.UpgradeKind.Rolling_NotificationOnly" />
      <MemberSignature Language="VB.NET" Value="Rolling_NotificationOnly" />
      <MemberSignature Language="F#" Value="Rolling_NotificationOnly = 3" Usage="System.Fabric.Description.UpgradeKind.Rolling_NotificationOnly" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.UpgradeKind</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>これは、ローリング アップグレードのレプリカは再起動がないことを示します。</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>