<Type Name="StatefulServiceLoadMetricDescription" FullName="System.Fabric.Description.StatefulServiceLoadMetricDescription">
  <TypeSignature Language="C#" Value="public sealed class StatefulServiceLoadMetricDescription : System.Fabric.Description.ServiceLoadMetricDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StatefulServiceLoadMetricDescription extends System.Fabric.Description.ServiceLoadMetricDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.StatefulServiceLoadMetricDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StatefulServiceLoadMetricDescription&#xA;Inherits ServiceLoadMetricDescription" />
  <TypeSignature Language="F#" Value="type StatefulServiceLoadMetricDescription = class&#xA;    inherit ServiceLoadMetricDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.ServiceLoadMetricDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>ステートフルなサービスのメトリックを指定します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StatefulServiceLoadMetricDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.StatefulServiceLoadMetricDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Description.StatefulServiceLoadMetricDescription" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryDefaultLoad">
      <MemberSignature Language="C#" Value="public int PrimaryDefaultLoad { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrimaryDefaultLoad" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceLoadMetricDescription.PrimaryDefaultLoad" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryDefaultLoad As Integer" />
      <MemberSignature Language="F#" Value="member this.PrimaryDefaultLoad : int with get, set" Usage="System.Fabric.Description.StatefulServiceLoadMetricDescription.PrimaryDefaultLoad" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または既定の負荷がプライマリ レプリカであるときに、このサービスが、この指標を作成する量を設定します。</para>
        </summary>
        <value>
          <para>既定では、負荷がプライマリ レプリカであるときに、このサービスがこのメトリックを作成したの時間。</para>
        </value>
        <remarks>
          <para>最初に作成されるときにサービスを効率的に配置する Service Fabric クラスター リソース マネージャーを使用するカスタム メトリックの既定の負荷の値を指定できます。        
             既定値を読み込む場合に、Service Fabric クラスター リソース マネージャーは、このサービスのプライマリ レプリカからの読み込みが報告するまで、このレプリカに対して 0 の負荷は想定を指定されていません。         
            <see cref="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" />       
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryDefaultLoad">
      <MemberSignature Language="C#" Value="public int SecondaryDefaultLoad { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 SecondaryDefaultLoad" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceLoadMetricDescription.SecondaryDefaultLoad" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryDefaultLoad As Integer" />
      <MemberSignature Language="F#" Value="member this.SecondaryDefaultLoad : int with get, set" Usage="System.Fabric.Description.StatefulServiceLoadMetricDescription.SecondaryDefaultLoad" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または既定の負荷がセカンダリ レプリカであるときに、このサービスが、この指標を作成する量を設定します。</para>
        </summary>
        <value>
          <para>既定がセカンダリ レプリカであるときに、このサービスがこのメトリックを作成した負荷の時間。</para>
        </value>
        <remarks>
          <para>最初に作成されるときにサービスを効率的に配置する Service Fabric クラスター リソース マネージャーを使用するカスタム メトリックの既定の負荷の値を指定できます。        
             既定値を読み込む場合に、Service Fabric クラスター リソース マネージャーは、このサービスのセカンダリ レプリカからの読み込みが報告するまで、このレプリカに対して 0 の負荷は想定を指定されていません。         
            <see cref="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" />        
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.StatefulServiceLoadMetricDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="statefulServiceLoadMetricDescription.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            詳細をかなり印刷<see cref="T:System.Fabric.Description.StatefulServiceLoadMetricDescription" />です。
            </summary>
        <returns><see cref="T:System.Fabric.Description.StatefulServiceLoadMetricDescription" /> の文字列形式。</returns>
        <remarks>To be added.</remarks>
        <example>
            CPU、高値、90、10
            </example>
      </Docs>
    </Member>
  </Members>
</Type>