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
      <para><span data-ttu-id="f78d3-101">アプリケーションのインスタンスまたはクラスターをアップグレードする場合、ローリング アップグレードの種類を指定します。</span><span class="sxs-lookup"><span data-stu-id="f78d3-101">Specifies the type of rolling upgrade when upgrading an application instance or cluster.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="f78d3-102">詳細については、アップグレードを参照してください、Service Fabric クラスターを拡張、およびアプリケーションをアップグレードします。</span><span class="sxs-lookup"><span data-stu-id="f78d3-102">For more information, see Upgrade and Scale a Service Fabric Cluster and Upgrade an Application.</span></span></para>
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
          <para><span data-ttu-id="f78d3-103">すべての Service Fabric の列挙には、無効なフラグが予約されています。</span><span class="sxs-lookup"><span data-stu-id="f78d3-103">All Service Fabric enumerations have reserved Invalid flag.</span></span></para>
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
          <para><span data-ttu-id="f78d3-104">アップグレードを自動監視する必要があることを指定します。</span><span class="sxs-lookup"><span data-stu-id="f78d3-104">Specifies that the upgrade should be monitored automatic.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="f78d3-105">アップグレード ドメイン (UD) のアップグレード後、Service Fabric は、UD とクラスターの正常性は、そのアップグレードの定義された正常性ポリシーを満たしている場合は [次へ] の UD、アップグレードに進みます。</span><span class="sxs-lookup"><span data-stu-id="f78d3-105">After an upgrade domain (UD) is upgraded, Service Fabric will proceed to upgrade the next UD if the health of the UD and the cluster meets the defined health policies for that upgrade.</span></span> <span data-ttu-id="f78d3-106">それ以外の場合、全体のアップグレードは失敗としてマークし、このアップグレードに失敗した操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="f78d3-106">Otherwise, the entire upgrade is marked as failed and the upgrade failure action is taken.</span></span> <span data-ttu-id="f78d3-107">既定のエラー アクションは、全体のアップグレードのロールバックがします。</span><span class="sxs-lookup"><span data-stu-id="f78d3-107">The default failure action is to roll-back the entire upgrade.</span></span></para>
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
          <para><span data-ttu-id="f78d3-108">アップグレードが監視されず自動をする必要がありますを指定します。</span><span class="sxs-lookup"><span data-stu-id="f78d3-108">Specifies that the upgrade should be unmonitored automatic.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="f78d3-109">このモードを使用して、すべてのアップグレード ドメインのアップグレードされるまでは、次のアップグレード ドメインをアップグレードする場合に自動的に続行されます。</span><span class="sxs-lookup"><span data-stu-id="f78d3-109">Using this mode,  automatically proceeds to upgrading the next upgrade domain until all upgrade domains are upgraded.</span></span></para>
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
          <para><span data-ttu-id="f78d3-110">アップグレードが監視されず手動をする必要がありますを指定します。</span><span class="sxs-lookup"><span data-stu-id="f78d3-110">Specifies that the upgrade should be unmonitored manual.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="f78d3-111">管理者はこのモードを使用して、次のアップグレード ドメインに移動するように指示する必要があります (を使用して、<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress)" />または<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.MoveNextFabricUpgradeDomainAsync(System.Fabric.FabricUpgradeProgress)" />メソッド) アップグレードを続行します。</span><span class="sxs-lookup"><span data-stu-id="f78d3-111">Using this mode, the administrator needs to instruct  to move to the next upgrade domain (using the <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress)" /> or <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.MoveNextFabricUpgradeDomainAsync(System.Fabric.FabricUpgradeProgress)" /> methods) and continue the upgrade.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>