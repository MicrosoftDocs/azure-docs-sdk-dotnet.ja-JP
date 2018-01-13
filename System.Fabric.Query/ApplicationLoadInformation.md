<Type Name="ApplicationLoadInformation" FullName="System.Fabric.Query.ApplicationLoadInformation">
  <TypeSignature Language="C#" Value="public class ApplicationLoadInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationLoadInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ApplicationLoadInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationLoadInformation" />
  <TypeSignature Language="F#" Value="type ApplicationLoadInformation = class" />
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
      <para> 使用して取得されるアプリケーション インスタンスの読み込みをについて説明します。<see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationLoadInformationAsync(System.String)" /></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationLoadInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ApplicationLoadInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Query.ApplicationLoadInformation" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationLoadMetricInformation">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Query.ApplicationLoadMetricInformation&gt; ApplicationLoadMetricInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.ApplicationLoadMetricInformation&gt; ApplicationLoadMetricInformation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationLoadInformation.ApplicationLoadMetricInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationLoadMetricInformation As IList(Of ApplicationLoadMetricInformation)" />
      <MemberSignature Language="F#" Value="member this.ApplicationLoadMetricInformation : System.Collections.Generic.IList&lt;System.Fabric.Query.ApplicationLoadMetricInformation&gt;" Usage="System.Fabric.Query.ApplicationLoadInformation.ApplicationLoadMetricInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Query.ApplicationLoadMetricInformation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このアプリケーション インスタンスのメトリックごとの読み込みの一覧を取得します。
            </summary>
        <value>
            このアプリケーション インスタンスのメトリックごとの読み込みの一覧。 定義されている各メトリックに関する<see cref="F:System.Fabric.Description.ApplicationDescription.Metrics" />アプリケーションの作成または更新されたときにある 1 つのインスタンス<see cref="T:System.Fabric.Query.ApplicationLoadMetricInformation" />この一覧にします。
            </value>
        <remarks>
            定義されたアプリケーションの容量がないアプリケーションをこの一覧は空になります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumNodes">
      <MemberSignature Language="C#" Value="public long MaximumNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaximumNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationLoadInformation.MaximumNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaximumNodes As Long" />
      <MemberSignature Language="F#" Value="member this.MaximumNodes : int64" Usage="System.Fabric.Query.ApplicationLoadInformation.MaximumNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このアプリケーションをインスタンス化するノードの最大数を取得します。
            </summary>
        <value>
          <para>
            スパンするこのアプリケーションが許可されているノードの数。
            この値は<see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" />アプリケーションの作成または更新されたときに設定しました。
            </para>
        </value>
        <remarks>
            定義されたアプリケーションの容量がないアプリケーションは、この値を 0 となります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimumNodes">
      <MemberSignature Language="C#" Value="public long MinimumNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MinimumNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationLoadInformation.MinimumNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MinimumNodes As Long" />
      <MemberSignature Language="F#" Value="member this.MinimumNodes : int64" Usage="System.Fabric.Query.ApplicationLoadInformation.MinimumNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このアプリケーションのノードの最小数を取得します。
            </summary>
        <value>
          <para>
            Service Fabric がこのアプリケーション インスタンスのクラスターの能力を確保、ノードの数。
            この値は<see cref="P:System.Fabric.Description.ApplicationDescription.MinimumNodes" />アプリケーションの作成または更新されたときに設定しました。
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationLoadInformation.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="System.Fabric.Query.ApplicationLoadInformation.Name" />
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
            アプリケーションの名前を取得または設定します。
            </summary>
        <value>
            アプリケーションの名前です。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeCount">
      <MemberSignature Language="C#" Value="public long NodeCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NodeCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationLoadInformation.NodeCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeCount As Long" />
      <MemberSignature Language="F#" Value="member this.NodeCount : int64" Usage="System.Fabric.Query.ApplicationLoadInformation.NodeCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このアプリケーションがインスタンス化されるノードの数を取得します。
            </summary>
        <value>
          <para>
            このアプリケーションがインスタンス化される現在のノードの数。
            </para>
        </value>
        <remarks>
            定義されたアプリケーションの容量がないアプリケーションは、この値を 0 となります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ApplicationLoadInformation.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationLoadInformation.ToString " />
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
          <para>
            詳細をかなり印刷<see cref="T:System.Fabric.Query.ApplicationLoadInformation" />です。
            </para>
        </summary>
        <returns><see cref="T:System.Fabric.Query.ApplicationLoadInformation" /> の文字列形式。</returns>
        <remarks>To be added.</remarks>
        <example>
            "ApplicationName":"fabric:/LoadBalancingAppType"、「最小ノード数」: 0、「最大ノード数」: 0、"NodeCount": 0、"ApplicationLoadMetricInformation":、
            </example>
      </Docs>
    </Member>
  </Members>
</Type>