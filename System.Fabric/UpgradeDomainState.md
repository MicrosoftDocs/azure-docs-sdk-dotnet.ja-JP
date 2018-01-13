<Type Name="UpgradeDomainState" FullName="System.Fabric.UpgradeDomainState">
  <TypeSignature Language="C#" Value="public enum UpgradeDomainState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed UpgradeDomainState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.UpgradeDomainState" />
  <TypeSignature Language="VB.NET" Value="Public Enum UpgradeDomainState" />
  <TypeSignature Language="F#" Value="type UpgradeDomainState = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>アップグレード ドメインの状態を列挙します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Completed">
      <MemberSignature Language="C#" Value="Completed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeDomainState Completed = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeDomainState.Completed" />
      <MemberSignature Language="VB.NET" Value="Completed" />
      <MemberSignature Language="F#" Value="Completed = 3" Usage="System.Fabric.UpgradeDomainState.Completed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeDomainState</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>アップグレードが完了したことを示します。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="InProgress">
      <MemberSignature Language="C#" Value="InProgress" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeDomainState InProgress = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeDomainState.InProgress" />
      <MemberSignature Language="VB.NET" Value="InProgress" />
      <MemberSignature Language="F#" Value="InProgress = 2" Usage="System.Fabric.UpgradeDomainState.InProgress" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeDomainState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>アップグレードが進行中であることを示します。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeDomainState Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeDomainState.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.UpgradeDomainState.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeDomainState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>このアップグレードが有効ではないことを示します。 無効な型であるすべての Service Fabric 列挙体。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Pending">
      <MemberSignature Language="C#" Value="Pending" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeDomainState Pending = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeDomainState.Pending" />
      <MemberSignature Language="VB.NET" Value="Pending" />
      <MemberSignature Language="F#" Value="Pending = 1" Usage="System.Fabric.UpgradeDomainState.Pending" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeDomainState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>アップグレードが保留中ですが開始されていないことを示します。</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>