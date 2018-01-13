<Type Name="VirtualMachineConfiguration" FullName="Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration">
  <TypeSignature Language="C#" Value="public class VirtualMachineConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineConfiguration" />
  <TypeSignature Language="F#" Value="type VirtualMachineConfiguration = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public VirtualMachineConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            VirtualMachineConfiguration クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineConfiguration (Microsoft.Azure.Management.Batch.Models.ImageReference imageReference, string nodeAgentSkuId, Microsoft.Azure.Management.Batch.Models.OSDisk osDisk = null, Microsoft.Azure.Management.Batch.Models.WindowsConfiguration windowsConfiguration = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.DataDisk&gt; dataDisks = null, string licenseType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Batch.Models.ImageReference imageReference, string nodeAgentSkuId, class Microsoft.Azure.Management.Batch.Models.OSDisk osDisk, class Microsoft.Azure.Management.Batch.Models.WindowsConfiguration windowsConfiguration, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.DataDisk&gt; dataDisks, string licenseType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.#ctor(Microsoft.Azure.Management.Batch.Models.ImageReference,System.String,Microsoft.Azure.Management.Batch.Models.OSDisk,Microsoft.Azure.Management.Batch.Models.WindowsConfiguration,System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.DataDisk},System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration : Microsoft.Azure.Management.Batch.Models.ImageReference * string * Microsoft.Azure.Management.Batch.Models.OSDisk * Microsoft.Azure.Management.Batch.Models.WindowsConfiguration * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.DataDisk&gt; * string -&gt; Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration" Usage="new Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration (imageReference, nodeAgentSkuId, osDisk, windowsConfiguration, dataDisks, licenseType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="imageReference" Type="Microsoft.Azure.Management.Batch.Models.ImageReference" />
        <Parameter Name="nodeAgentSkuId" Type="System.String" />
        <Parameter Name="osDisk" Type="Microsoft.Azure.Management.Batch.Models.OSDisk" />
        <Parameter Name="windowsConfiguration" Type="Microsoft.Azure.Management.Batch.Models.WindowsConfiguration" />
        <Parameter Name="dataDisks" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.DataDisk&gt;" />
        <Parameter Name="licenseType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageReference">使用するには、Azure の仮想マシンの Marketplace イメージまたはカスタムの仮想マシンのイメージへの参照。</param>
        <param name="nodeAgentSkuId">プロビジョニングする Batch ノード エージェント SKU では、プール内のノードを計算します。</param>
        <param name="osDisk">仮想マシンのオペレーティング システム ディスクの設定です。</param>
        <param name="windowsConfiguration">仮想マシンで Windows オペレーティング システムの設定です。</param>
        <param name="dataDisks">プール内の comptue ノードに接続されているデータ ディスクの構成。</param>
        <param name="licenseType">オペレーティング システムを展開するときに使用される内部設置型ライセンスの種類。</param>
        <summary>
            VirtualMachineConfiguration クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataDisks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.DataDisk&gt; DataDisks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.DataDisk&gt; DataDisks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.DataDisks" />
      <MemberSignature Language="VB.NET" Value="Public Property DataDisks As IList(Of DataDisk)" />
      <MemberSignature Language="F#" Value="member this.DataDisks : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.DataDisk&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.DataDisks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataDisks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.DataDisk&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプール内の comptue ノードに接続されているデータ ディスクの構成を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティを指定する必要があります指定されたかどうか、プール内の計算ノードは空のデータ ディスクを関連付けることがある必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ImageReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.ImageReference ImageReference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.ImageReference ImageReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.ImageReference" />
      <MemberSignature Language="VB.NET" Value="Public Property ImageReference As ImageReference" />
      <MemberSignature Language="F#" Value="member this.ImageReference : Microsoft.Azure.Management.Batch.Models.ImageReference with get, set" Usage="Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.ImageReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="imageReference")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.ImageReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または使用するには、Azure の仮想マシン Marketplace イメージを使用すると、またはカスタムの仮想マシンのイメージへの参照を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LicenseType">
      <MemberSignature Language="C#" Value="public string LicenseType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LicenseType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.LicenseType" />
      <MemberSignature Language="VB.NET" Value="Public Property LicenseType As String" />
      <MemberSignature Language="F#" Value="member this.LicenseType : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.LicenseType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="licenseType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             取得またはオペレーティング システムを展開するときに使用される内部設置型ライセンスの種類を設定します。
             </summary>
        <value>To be added.</value>
        <remarks>
             これは、Windows オペレーティング システムが含まれており、展開するノードの有効な内部設置型ライセンスを保持する場合にのみ使用されるイメージにのみ適用されます。 省略した場合、なし、内部設置型ライセンス割引が適用されます。 値は次のとおりです。
             
             Windows Server は、内部設置型ライセンス Windows_Server - です。
             Windows クライアントは、内部設置型ライセンス Windows_Client - です。
            
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeAgentSkuId">
      <MemberSignature Language="C#" Value="public string NodeAgentSkuId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeAgentSkuId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.NodeAgentSkuId" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeAgentSkuId As String" />
      <MemberSignature Language="F#" Value="member this.NodeAgentSkuId : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.NodeAgentSkuId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeAgentSkuId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定をプール内の計算ノードで提供するバッチ ノード エージェント SKU。
            </summary>
        <value>To be added.</value>
        <remarks>
            Batch ノード エージェントは、プール内の各ノード上で実行され、ノードと、バッチ サービスの間のコマンドとコントロール インターフェイスを提供するプログラムです。 オペレーティング システムに応じてさまざまなノード エージェントの実装 (SKU と呼ばれます) があります。 ノード エージェント SKU 選択した画像の参照に一致するを指定する必要があります。 検証済みのイメージの参照の一覧と共にサポートされているノード エージェント Sku の一覧を取得するには、'リストには、ノード エージェント Sku がサポートされている' 操作を参照してください。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OsDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.OSDisk OsDisk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.OSDisk OsDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.OsDisk" />
      <MemberSignature Language="VB.NET" Value="Public Property OsDisk As OSDisk" />
      <MemberSignature Language="F#" Value="member this.OsDisk : Microsoft.Azure.Management.Batch.Models.OSDisk with get, set" Usage="Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.OsDisk" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osDisk")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.OSDisk</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または仮想マシンのオペレーティング システム ディスクの設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualMachineConfiguration.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="WindowsConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.WindowsConfiguration WindowsConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.WindowsConfiguration WindowsConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.WindowsConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsConfiguration As WindowsConfiguration" />
      <MemberSignature Language="F#" Value="member this.WindowsConfiguration : Microsoft.Azure.Management.Batch.Models.WindowsConfiguration with get, set" Usage="Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration.WindowsConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="windowsConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.WindowsConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または仮想マシンで windows オペレーティング システムの設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティにはできません、imageReference が Linux OS イメージを指定するかどうかを指定します。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>