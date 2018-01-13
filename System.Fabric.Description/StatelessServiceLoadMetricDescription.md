<Type Name="StatelessServiceLoadMetricDescription" FullName="System.Fabric.Description.StatelessServiceLoadMetricDescription">
  <TypeSignature Language="C#" Value="public sealed class StatelessServiceLoadMetricDescription : System.Fabric.Description.ServiceLoadMetricDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StatelessServiceLoadMetricDescription extends System.Fabric.Description.ServiceLoadMetricDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.StatelessServiceLoadMetricDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StatelessServiceLoadMetricDescription&#xA;Inherits ServiceLoadMetricDescription" />
  <TypeSignature Language="F#" Value="type StatelessServiceLoadMetricDescription = class&#xA;    inherit ServiceLoadMetricDescription" />
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
      <para>ステートレス サービスのメトリックを指定します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StatelessServiceLoadMetricDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.StatelessServiceLoadMetricDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Description.StatelessServiceLoadMetricDescription" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultLoad">
      <MemberSignature Language="C#" Value="public int DefaultLoad { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DefaultLoad" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatelessServiceLoadMetricDescription.DefaultLoad" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultLoad As Integer" />
      <MemberSignature Language="F#" Value="member this.DefaultLoad : int with get, set" Usage="System.Fabric.Description.StatelessServiceLoadMetricDescription.DefaultLoad" />
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
          <para>取得または既定のこのサービスは、この指標を作成する負荷の量を設定します。</para>
        </summary>
        <value>
          <para>既定では、このサービスは、この指標の作成の負荷の時間。</para>
        </value>
        <remarks>
          <para>最初に作成されるときにサービスを効率的に配置する Service Fabric クラスター リソース マネージャーを使用するカスタム メトリックの既定の負荷の値を指定できます。
            既定値を読み込む場合に、Service Fabric クラスター リソース マネージャーは、サービスからの読み込みが報告するまで、このレプリカに対して 0 の負荷は想定を指定されていません。
            <see cref="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" />
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.StatelessServiceLoadMetricDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="statelessServiceLoadMetricDescription.ToString " />
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
            詳細をかなり印刷<see cref="T:System.Fabric.Description.StatelessServiceLoadMetricDescription" />です。
            </summary>
        <returns><see cref="T:System.Fabric.Description.StatelessServiceLoadMetricDescription" /> の文字列形式。</returns>
        <remarks>To be added.</remarks>
        <example>
            CPU、高値、90
            </example>
      </Docs>
    </Member>
  </Members>
</Type>