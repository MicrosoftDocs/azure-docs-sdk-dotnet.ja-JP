<Type Name="PoolUsageMetrics" FullName="Microsoft.Azure.Batch.PoolUsageMetrics">
  <TypeSignature Language="C#" Value="public class PoolUsageMetrics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolUsageMetrics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.PoolUsageMetrics" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolUsageMetrics" />
  <TypeSignature Language="F#" Value="type PoolUsageMetrics = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            特定の時間の範囲内の 1 つのプールの使用状況メトリック。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DataEgressGiB">
      <MemberSignature Language="C#" Value="public double DataEgressGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 DataEgressGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolUsageMetrics.DataEgressGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataEgressGiB As Double" />
      <MemberSignature Language="F#" Value="member this.DataEgressGiB : double" Usage="Microsoft.Azure.Batch.PoolUsageMetrics.DataEgressGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibibytes で、この間隔中に、プールからの間のデータ センター ネットワーク送信を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataIngressGiB">
      <MemberSignature Language="C#" Value="public double DataIngressGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 DataIngressGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolUsageMetrics.DataIngressGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataIngressGiB As Double" />
      <MemberSignature Language="F#" Value="member this.DataIngressGiB : double" Usage="Microsoft.Azure.Batch.PoolUsageMetrics.DataIngressGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibibytes で、この間隔中には、プールには、クロス データ センター ネットワーク受信を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public DateTime EndTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolUsageMetrics.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.EndTime : DateTime" Usage="Microsoft.Azure.Batch.PoolUsageMetrics.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このエントリの集計間隔の終了時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolId">
      <MemberSignature Language="C#" Value="public string PoolId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PoolId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolUsageMetrics.PoolId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PoolId As String" />
      <MemberSignature Language="F#" Value="member this.PoolId : string" Usage="Microsoft.Azure.Batch.PoolUsageMetrics.PoolId" />
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
            このエントリであるメトリックが集計されて、プールの id を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolUsageMetrics.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime" Usage="Microsoft.Azure.Batch.PoolUsageMetrics.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このエントリに含まれる集計範囲の開始時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCoreHours">
      <MemberSignature Language="C#" Value="public double TotalCoreHours { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 TotalCoreHours" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolUsageMetrics.TotalCoreHours" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCoreHours As Double" />
      <MemberSignature Language="F#" Value="member this.TotalCoreHours : double" Usage="Microsoft.Azure.Batch.PoolUsageMetrics.TotalCoreHours" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この集計間隔の間に、プールで使用される合計コア時間を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineSize">
      <MemberSignature Language="C#" Value="public string VirtualMachineSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualMachineSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolUsageMetrics.VirtualMachineSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineSize As String" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineSize : string" Usage="Microsoft.Azure.Batch.PoolUsageMetrics.VirtualMachineSize" />
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
            プール内の仮想マシンのサイズを取得します。  プール内の仮想マシンのサイズはすべて同じです。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>クラウド サービス プールの仮想マシンの利用可能なサイズについて (で作成されたプール、 <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />)、https://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/ を参照してください。 バッチには、ExtraSmall を除くすべてのクラウド サービス VM サイズがサポートしています。</para>
          <para>仮想マシンのマーケットプ レースからイメージを使用するプールの利用可能な VM サイズについては (で作成されたプール、 <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />) https://azure.microsoft.com/documentation/articles/virtual-machines-linux-sizes/ または https:// を参照してくださいazure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/ です。 バッチには、STANDARD_A0 と premium storage (たとえば STANDARD_GS、STANDARD_DS、および STANDARD_DSV2 シリーズ) でそれらを除くすべての Azure VM サイズがサポートしています。</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>