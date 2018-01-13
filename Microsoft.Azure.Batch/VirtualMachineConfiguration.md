<Type Name="VirtualMachineConfiguration" FullName="Microsoft.Azure.Batch.VirtualMachineConfiguration">
  <TypeSignature Language="C#" Value="public class VirtualMachineConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineConfiguration" />
  <TypeSignature Language="F#" Value="type VirtualMachineConfiguration = class&#xA;    interface ITransportObjectProvider&lt;VirtualMachineConfiguration&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            構成は、Azure Virtual Machines インフラストラクチャに基づいて、プール内のノードを計算します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineConfiguration (Microsoft.Azure.Batch.ImageReference imageReference, string nodeAgentSkuId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.ImageReference imageReference, string nodeAgentSkuId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.VirtualMachineConfiguration.#ctor(Microsoft.Azure.Batch.ImageReference,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.VirtualMachineConfiguration : Microsoft.Azure.Batch.ImageReference * string -&gt; Microsoft.Azure.Batch.VirtualMachineConfiguration" Usage="new Microsoft.Azure.Batch.VirtualMachineConfiguration (imageReference, nodeAgentSkuId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="imageReference" Type="Microsoft.Azure.Batch.ImageReference" />
        <Parameter Name="nodeAgentSkuId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageReference">使用するには、Azure の仮想マシンの Marketplace イメージまたはカスタムの仮想マシンのイメージへの参照。</param>
        <param name="nodeAgentSkuId">SKU の Batch ノード エージェントをコンピューティング ノードで提供します。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ContainerConfiguration ContainerConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ContainerConfiguration ContainerConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.ContainerConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerConfiguration As ContainerConfiguration" />
      <MemberSignature Language="F#" Value="member this.ContainerConfiguration : Microsoft.Azure.Batch.ContainerConfiguration with get, set" Usage="Microsoft.Azure.Batch.VirtualMachineConfiguration.ContainerConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ContainerConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプールのコンテナーの構成を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            指定した場合、プール内のコンテナーでタスクを実行できるようにするには、各ノードでセットアップを実行します。 すべての正規のタスクとこのプールで実行されるジョブ マネージャー タスクを指定する必要があります<see cref="T:Microsoft.Azure.Batch.TaskContainerSettings" />、し、その他のすべてのタスクが指定可能性があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DataDisks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.DataDisk&gt; DataDisks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.DataDisk&gt; DataDisks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.DataDisks" />
      <MemberSignature Language="VB.NET" Value="Public Property DataDisks As IList(Of DataDisk)" />
      <MemberSignature Language="F#" Value="member this.DataDisks : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.DataDisk&gt; with get, set" Usage="Microsoft.Azure.Batch.VirtualMachineConfiguration.DataDisks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.DataDisk&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプール内の Comptue ノードに接続されているデータ ディスクの構成を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティを指定する必要があります指定されたかどうか、プール内のコンピューティング ノードは空のデータ ディスクを関連付けることがある必要があります。 これは更新できません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ImageReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ImageReference ImageReference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ImageReference ImageReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.ImageReference" />
      <MemberSignature Language="VB.NET" Value="Public Property ImageReference As ImageReference" />
      <MemberSignature Language="F#" Value="member this.ImageReference : Microsoft.Azure.Batch.ImageReference with get, set" Usage="Microsoft.Azure.Batch.VirtualMachineConfiguration.ImageReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ImageReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または使用するには、Azure の仮想マシン Marketplace イメージを使用すると、またはカスタムの仮想マシンのイメージへの参照を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティと<see cref="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.OSDisk" />は相互に排他的プロパティのいずれかを指定する必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LicenseType">
      <MemberSignature Language="C#" Value="public string LicenseType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LicenseType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.LicenseType" />
      <MemberSignature Language="VB.NET" Value="Public Property LicenseType As String" />
      <MemberSignature Language="F#" Value="member this.LicenseType : string with get, set" Usage="Microsoft.Azure.Batch.VirtualMachineConfiguration.LicenseType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはオペレーティング システムを展開するときに使用される内部設置型ライセンスの種類を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            これは、Windows オペレーティング システムが含まれており、展開するノードの有効な内部設置型ライセンスを保持する場合にのみ使用されるイメージにのみ適用されます。 省略した場合、なし、内部設置型ライセンス割引が適用されます。 値が: 'Windows_Server' - Windows Server は、内部設置型ライセンス。 Windows クライアントは、内部設置型ライセンス 'Windows_Client' - です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeAgentSkuId">
      <MemberSignature Language="C#" Value="public string NodeAgentSkuId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeAgentSkuId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.NodeAgentSkuId" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeAgentSkuId As String" />
      <MemberSignature Language="F#" Value="member this.NodeAgentSkuId : string with get, set" Usage="Microsoft.Azure.Batch.VirtualMachineConfiguration.NodeAgentSkuId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または SKU のバッチのノードにエージェントをコンピューティング ノード上でプロビジョニングするを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            Batch ノード エージェントは、プール内の各ノード上で実行され、ノードと、バッチ サービスの間のコマンドとコントロール インターフェイスを提供するプログラムです。 オペレーティング システムに応じてさまざまなノード エージェントの実装 (SKU と呼ばれます) があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OSDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.OSDisk OSDisk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.OSDisk OSDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.OSDisk" />
      <MemberSignature Language="VB.NET" Value="Public Property OSDisk As OSDisk" />
      <MemberSignature Language="F#" Value="member this.OSDisk : Microsoft.Azure.Batch.OSDisk with get, set" Usage="Microsoft.Azure.Batch.VirtualMachineConfiguration.OSDisk" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.OSDisk</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または仮想マシンのオペレーティング システム ディスクの設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティに指定できる Batch アカウントが、poolAllocationMode プロパティ 'UserSubscription' に設定して作成されたかどうかにのみ指定します。 このプロパティと<see cref="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.ImageReference" />は相互に排他的プロパティのいずれかを指定する必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowsConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.WindowsConfiguration WindowsConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.WindowsConfiguration WindowsConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.VirtualMachineConfiguration.WindowsConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsConfiguration As WindowsConfiguration" />
      <MemberSignature Language="F#" Value="member this.WindowsConfiguration : Microsoft.Azure.Batch.WindowsConfiguration with get, set" Usage="Microsoft.Azure.Batch.VirtualMachineConfiguration.WindowsConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.WindowsConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または仮想マシンで windows オペレーティング システムの設定を設定します。 このプロパティにはできません、ImageReference プロパティが Linux OS イメージを指定するかどうかを指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>