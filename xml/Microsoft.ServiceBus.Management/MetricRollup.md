<Type Name="MetricRollup" FullName="Microsoft.ServiceBus.Management.MetricRollup">
  <TypeSignature Language="C#" Value="public class MetricRollup" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetricRollup extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Management.MetricRollup" />
  <TypeSignature Language="VB.NET" Value="Public Class MetricRollup" />
  <TypeSignature Language="F#" Value="type MetricRollup = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="adef0-101">Service Bus メトリックのロールアップ データを表します。</span><span class="sxs-lookup"><span data-stu-id="adef0-101">Represents the rollup data for Service Bus metrics.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricRollup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Management.MetricRollup.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retention">
      <MemberSignature Language="C#" Value="public TimeSpan Retention { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan Retention" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.MetricRollup.Retention" />
      <MemberSignature Language="VB.NET" Value="Public Property Retention As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.Retention : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Management.MetricRollup.Retention" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="adef0-102">取得またはロールアップに関連付けられている保有期間の時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="adef0-102">Gets or sets the time of the retention associated with the rollup.</span></span></summary>
        <value><span data-ttu-id="adef0-103">ロールアップに関連付けられている保有期間の時刻。</span><span class="sxs-lookup"><span data-stu-id="adef0-103">The time of the retention associated with the rollup.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeGrain">
      <MemberSignature Language="C#" Value="public TimeSpan TimeGrain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeGrain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.MetricRollup.TimeGrain" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeGrain As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeGrain : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Management.MetricRollup.TimeGrain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.DataAnnotations.Key</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="adef0-104">取得またはロールアップに関連付けられている時間の単位を設定します。</span><span class="sxs-lookup"><span data-stu-id="adef0-104">Gets or sets the time grain associated with the rollup.</span></span></summary>
        <value><span data-ttu-id="adef0-105">ロールアップに関連付けられている時間の単位。</span><span class="sxs-lookup"><span data-stu-id="adef0-105">The time grain associated with the rollup.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Values">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ICollection&lt;Microsoft.ServiceBus.Management.MetricValue&gt; Values { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ICollection`1&lt;class Microsoft.ServiceBus.Management.MetricValue&gt; Values" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.MetricRollup.Values" />
      <MemberSignature Language="VB.NET" Value="Public Property Values As ICollection(Of MetricValue)" />
      <MemberSignature Language="F#" Value="member this.Values : System.Collections.Generic.ICollection&lt;Microsoft.ServiceBus.Management.MetricValue&gt; with get, set" Usage="Microsoft.ServiceBus.Management.MetricRollup.Values" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ICollection&lt;Microsoft.ServiceBus.Management.MetricValue&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="adef0-106">取得またはメトリックの値のコレクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="adef0-106">Gets or sets the collection of metric values.</span></span></summary>
        <value><span data-ttu-id="adef0-107">メトリックの値のコレクション。</span><span class="sxs-lookup"><span data-stu-id="adef0-107">The collection of metric values.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>