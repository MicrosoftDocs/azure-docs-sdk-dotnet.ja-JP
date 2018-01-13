<Type Name="ComposeDeploymentUpgradeState" FullName="System.Fabric.ComposeDeploymentUpgradeState">
  <TypeSignature Language="C#" Value="public enum ComposeDeploymentUpgradeState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ComposeDeploymentUpgradeState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ComposeDeploymentUpgradeState" />
  <TypeSignature Language="VB.NET" Value="Public Enum ComposeDeploymentUpgradeState" />
  <TypeSignature Language="F#" Value="type ComposeDeploymentUpgradeState = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>作成する配置のアップグレードの状態を列挙します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Failed">
      <MemberSignature Language="C#" Value="Failed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ComposeDeploymentUpgradeState Failed = int32(9)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ComposeDeploymentUpgradeState.Failed" />
      <MemberSignature Language="VB.NET" Value="Failed" />
      <MemberSignature Language="F#" Value="Failed = 9" Usage="System.Fabric.ComposeDeploymentUpgradeState.Failed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ComposeDeploymentUpgradeState</ReturnType>
      </ReturnValue>
      <MemberValue>9</MemberValue>
      <Docs>
        <summary>
          <para>アップグレードが失敗したことを示します。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ComposeDeploymentUpgradeState Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ComposeDeploymentUpgradeState.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.ComposeDeploymentUpgradeState.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ComposeDeploymentUpgradeState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>型が無効であることを示します。 すべての Service Fabric の列挙には、無効な型があります。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningTarget">
      <MemberSignature Language="C#" Value="ProvisioningTarget" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ComposeDeploymentUpgradeState ProvisioningTarget = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ComposeDeploymentUpgradeState.ProvisioningTarget" />
      <MemberSignature Language="VB.NET" Value="ProvisioningTarget" />
      <MemberSignature Language="F#" Value="ProvisioningTarget = 1" Usage="System.Fabric.ComposeDeploymentUpgradeState.ProvisioningTarget" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ComposeDeploymentUpgradeState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>示すプロビジョニングされているが、対象のアプリケーションの種類が展開を作成します。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="RollingBackCompleted">
      <MemberSignature Language="C#" Value="RollingBackCompleted" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ComposeDeploymentUpgradeState RollingBackCompleted = int32(8)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ComposeDeploymentUpgradeState.RollingBackCompleted" />
      <MemberSignature Language="VB.NET" Value="RollingBackCompleted" />
      <MemberSignature Language="F#" Value="RollingBackCompleted = 8" Usage="System.Fabric.ComposeDeploymentUpgradeState.RollingBackCompleted" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ComposeDeploymentUpgradeState</ReturnType>
      </ReturnValue>
      <MemberValue>8</MemberValue>
      <Docs>
        <summary>
          <para>アップグレードのロールバックが完了したことを示します。 ロールバックの完了がアップグレードを示す、ターゲットにバージョンが失敗しました。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="RollingBackInProgress">
      <MemberSignature Language="C#" Value="RollingBackInProgress" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ComposeDeploymentUpgradeState RollingBackInProgress = int32(6)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ComposeDeploymentUpgradeState.RollingBackInProgress" />
      <MemberSignature Language="VB.NET" Value="RollingBackInProgress" />
      <MemberSignature Language="F#" Value="RollingBackInProgress = 6" Usage="System.Fabric.ComposeDeploymentUpgradeState.RollingBackInProgress" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ComposeDeploymentUpgradeState</ReturnType>
      </ReturnValue>
      <MemberValue>6</MemberValue>
      <Docs>
        <summary>
          <para>アップグレードがロールバック処理中にあることを示します。 これは、ターゲットにアップグレードを示します作成配置に失敗しました。 この状態もなお、アップグレードが新しいアップグレードを開始する中断されているかどうかは一時的に計測されました。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="RollingForwardCompleted">
      <MemberSignature Language="C#" Value="RollingForwardCompleted" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ComposeDeploymentUpgradeState RollingForwardCompleted = int32(5)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ComposeDeploymentUpgradeState.RollingForwardCompleted" />
      <MemberSignature Language="VB.NET" Value="RollingForwardCompleted" />
      <MemberSignature Language="F#" Value="RollingForwardCompleted = 5" Usage="System.Fabric.ComposeDeploymentUpgradeState.RollingForwardCompleted" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ComposeDeploymentUpgradeState</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
          <para>示す完了ターゲットへのアップグレードが展開を作成します。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="RollingForwardInProgress">
      <MemberSignature Language="C#" Value="RollingForwardInProgress" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ComposeDeploymentUpgradeState RollingForwardInProgress = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ComposeDeploymentUpgradeState.RollingForwardInProgress" />
      <MemberSignature Language="VB.NET" Value="RollingForwardInProgress" />
      <MemberSignature Language="F#" Value="RollingForwardInProgress = 2" Usage="System.Fabric.ComposeDeploymentUpgradeState.RollingForwardInProgress" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ComposeDeploymentUpgradeState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>示す進行状況では、ターゲットへのアップグレードが展開を作成します。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="RollingForwardPending">
      <MemberSignature Language="C#" Value="RollingForwardPending" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ComposeDeploymentUpgradeState RollingForwardPending = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ComposeDeploymentUpgradeState.RollingForwardPending" />
      <MemberSignature Language="VB.NET" Value="RollingForwardPending" />
      <MemberSignature Language="F#" Value="RollingForwardPending = 3" Usage="System.Fabric.ComposeDeploymentUpgradeState.RollingForwardPending" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ComposeDeploymentUpgradeState</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>示す保留中のユーザー入力は、ターゲットへのアップグレードが展開を作成します。 <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress)" />アップグレードを前方に移動するために使用します。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="UnprovisioningCurrent">
      <MemberSignature Language="C#" Value="UnprovisioningCurrent" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ComposeDeploymentUpgradeState UnprovisioningCurrent = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ComposeDeploymentUpgradeState.UnprovisioningCurrent" />
      <MemberSignature Language="VB.NET" Value="UnprovisioningCurrent" />
      <MemberSignature Language="F#" Value="UnprovisioningCurrent = 4" Usage="System.Fabric.ComposeDeploymentUpgradeState.UnprovisioningCurrent" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ComposeDeploymentUpgradeState</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para>示す現在のアプリケーションの種類が展開を作成することはされている準備を解除します。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="UnprovisioningTarget">
      <MemberSignature Language="C#" Value="UnprovisioningTarget" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ComposeDeploymentUpgradeState UnprovisioningTarget = int32(7)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ComposeDeploymentUpgradeState.UnprovisioningTarget" />
      <MemberSignature Language="VB.NET" Value="UnprovisioningTarget" />
      <MemberSignature Language="F#" Value="UnprovisioningTarget = 7" Usage="System.Fabric.ComposeDeploymentUpgradeState.UnprovisioningTarget" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ComposeDeploymentUpgradeState</ReturnType>
      </ReturnValue>
      <MemberValue>7</MemberValue>
      <Docs>
        <summary>
          <para>示すターゲットのアプリケーションの種類が展開を作成することはされている準備を解除します。 この状態が表示されている、アップグレードが失敗したアップグレードがロールバックされていることを示します。</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>