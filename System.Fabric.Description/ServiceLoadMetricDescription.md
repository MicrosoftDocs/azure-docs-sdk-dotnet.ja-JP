<Type Name="ServiceLoadMetricDescription" FullName="System.Fabric.Description.ServiceLoadMetricDescription">
  <TypeSignature Language="C#" Value="public class ServiceLoadMetricDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceLoadMetricDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceLoadMetricDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceLoadMetricDescription" />
  <TypeSignature Language="F#" Value="type ServiceLoadMetricDescription = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>実行時に負荷を分散するメトリック、サービスを指定します。</para>
    </summary>
    <remarks>
      <para>Service Fabric は、既定のメトリックを使用するために、サービスのメトリックは省略可能で提供することに注意してください。 高度な負荷が分散される分散などの機能が特定のノードの特性およびリソースに基づいて、サービスに必要な場合にのみ、メトリックを提供します。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceLoadMetricDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceLoadMetricDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Description.ServiceLoadMetricDescription" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceLoadMetricDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="System.Fabric.Description.ServiceLoadMetricDescription.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはメトリックの名前を設定します。 </para>
        </summary>
        <value>
          <para>メトリックの名前。</para>
        </value>
        <remarks>
          <para>サービスを選択した場合<see cref="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" />実行時に経由で指定された名前、<see cref="T:System.Fabric.LoadMetric" />時間をで指定されている名前に一致する必要があります<see cref="P:System.Fabric.Description.ServiceLoadMetricDescription.Name" />正確にします。</para>
          <para>メトリック名は大文字小文字を区別ことに注意してください。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryDefaultLoad">
      <MemberSignature Language="C#" Value="public int PrimaryDefaultLoad { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrimaryDefaultLoad" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceLoadMetricDescription.PrimaryDefaultLoad" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryDefaultLoad As Integer" />
      <MemberSignature Language="F#" Value="member this.PrimaryDefaultLoad : int with get, set" Usage="System.Fabric.Description.ServiceLoadMetricDescription.PrimaryDefaultLoad" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("PrimaryDefaultLoad in ServiceLoadMetricDescription is deprecated, please use StatefulServiceLoadMetricDescription instead.", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>派生クラスを参照してください<see cref="T:System.Fabric.Description.StatefulServiceLoadMetricDescription" />または<see cref="T:System.Fabric.Description.StatelessServiceLoadMetricDescription" />使用法をします。</para>
        </summary>
        <value>To be added.</value>
        <remarks>
          <para>このプロパティは使用しないで、派生クラスで対応するプロパティを使用してください。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryDefaultLoad">
      <MemberSignature Language="C#" Value="public int SecondaryDefaultLoad { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 SecondaryDefaultLoad" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceLoadMetricDescription.SecondaryDefaultLoad" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryDefaultLoad As Integer" />
      <MemberSignature Language="F#" Value="member this.SecondaryDefaultLoad : int with get, set" Usage="System.Fabric.Description.ServiceLoadMetricDescription.SecondaryDefaultLoad" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("SecondaryDefaultLoad in ServiceLoadMetricDescription is deprecated, please use StatefulServiceLoadMetricDescription instead.", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>派生クラスを参照してください<see cref="T:System.Fabric.Description.StatefulServiceLoadMetricDescription" />または<see cref="T:System.Fabric.Description.StatelessServiceLoadMetricDescription" />使用法をします。</para>
        </summary>
        <value>To be added.</value>
        <remarks>
          <para>このプロパティは使用しないで、派生クラスで対応するプロパティを使用してください。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public string ToString (bool isStateful);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string ToString(bool isStateful) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceLoadMetricDescription.ToString(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToString (isStateful As Boolean) As String" />
      <MemberSignature Language="F#" Value="override this.ToString : bool -&gt; string" Usage="serviceLoadMetricDescription.ToString isStateful" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="isStateful" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="isStateful">To be added.</param>
        <summary>
            詳細をかなり印刷<see cref="T:System.Fabric.Description.StatefulServiceLoadMetricDescription" />または<see cref="T:System.Fabric.Description.StatelessServiceLoadMetricDescription" />です。
            </summary>
        <returns>文字列表現<see cref="T:System.Fabric.Description.StatefulServiceLoadMetricDescription" />または<see cref="T:System.Fabric.Description.StatelessServiceLoadMetricDescription" />です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Weight">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ServiceLoadMetricWeight Weight { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.ServiceLoadMetricWeight Weight" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceLoadMetricDescription.Weight" />
      <MemberSignature Language="VB.NET" Value="Public Property Weight As ServiceLoadMetricWeight" />
      <MemberSignature Language="F#" Value="member this.Weight : System.Fabric.Description.ServiceLoadMetricWeight with get, set" Usage="System.Fabric.Description.ServiceLoadMetricDescription.Weight" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceLoadMetricWeight</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>このサービスが構成されている他のメトリックを基準としたメトリックの重みを決定します。 実行時に、競合で 2 つのメトリックが終了する場合、クラスター リソース マネージャーによっては大きな重みのメトリックが優先されます。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.Description.ServiceLoadMetricWeight" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>