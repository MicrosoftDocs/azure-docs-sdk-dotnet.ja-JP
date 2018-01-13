<Type Name="RollingUpgradeMode" FullName="System.Fabric.RollingUpgradeMode">
  <TypeSignature Language="C#" Value="public enum RollingUpgradeMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed RollingUpgradeMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.RollingUpgradeMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum RollingUpgradeMode" />
  <TypeSignature Language="F#" Value="type RollingUpgradeMode = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>アプリケーションのインスタンスまたはクラスターをアップグレードする場合、ローリング アップグレードの種類を指定します。</para>
    </summary>
    <remarks>
      <para>詳細については、アップグレードを参照してください、Service Fabric クラスターを拡張、およびアプリケーションをアップグレードします。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.RollingUpgradeMode Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.RollingUpgradeMode.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.RollingUpgradeMode.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.RollingUpgradeMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>すべての Service Fabric の列挙には、無効なフラグが予約されています。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Monitored">
      <MemberSignature Language="C#" Value="Monitored" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.RollingUpgradeMode Monitored = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.RollingUpgradeMode.Monitored" />
      <MemberSignature Language="VB.NET" Value="Monitored" />
      <MemberSignature Language="F#" Value="Monitored = 3" Usage="System.Fabric.RollingUpgradeMode.Monitored" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.RollingUpgradeMode</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>アップグレードを自動監視する必要があることを指定します。</para>
        </summary>
        <remarks>
          <para>アップグレード ドメイン (UD) のアップグレード後、Service Fabric は、UD とクラスターの正常性は、そのアップグレードの定義された正常性ポリシーを満たしている場合は [次へ] の UD、アップグレードに進みます。 それ以外の場合、全体のアップグレードは失敗としてマークし、このアップグレードに失敗した操作を実行します。 既定のエラー アクションは、全体のアップグレードのロールバックがします。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UnmonitoredAuto">
      <MemberSignature Language="C#" Value="UnmonitoredAuto" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.RollingUpgradeMode UnmonitoredAuto = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.RollingUpgradeMode.UnmonitoredAuto" />
      <MemberSignature Language="VB.NET" Value="UnmonitoredAuto" />
      <MemberSignature Language="F#" Value="UnmonitoredAuto = 1" Usage="System.Fabric.RollingUpgradeMode.UnmonitoredAuto" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.RollingUpgradeMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>アップグレードが監視されず自動をする必要がありますを指定します。</para>
        </summary>
        <remarks>
          <para>このモードを使用して、すべてのアップグレード ドメインのアップグレードされるまでは、次のアップグレード ドメインをアップグレードする場合に自動的に続行されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UnmonitoredManual">
      <MemberSignature Language="C#" Value="UnmonitoredManual" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.RollingUpgradeMode UnmonitoredManual = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.RollingUpgradeMode.UnmonitoredManual" />
      <MemberSignature Language="VB.NET" Value="UnmonitoredManual" />
      <MemberSignature Language="F#" Value="UnmonitoredManual = 2" Usage="System.Fabric.RollingUpgradeMode.UnmonitoredManual" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.RollingUpgradeMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>アップグレードが監視されず手動をする必要がありますを指定します。</para>
        </summary>
        <remarks>
          <para>管理者はこのモードを使用して、次のアップグレード ドメインに移動するように指示する必要があります (を使用して、<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress)" />または<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.MoveNextFabricUpgradeDomainAsync(System.Fabric.FabricUpgradeProgress)" />メソッド) アップグレードを続行します。</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>