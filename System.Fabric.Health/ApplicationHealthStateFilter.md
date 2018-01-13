<Type Name="ApplicationHealthStateFilter" FullName="System.Fabric.Health.ApplicationHealthStateFilter">
  <TypeSignature Language="C#" Value="public sealed class ApplicationHealthStateFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationHealthStateFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ApplicationHealthStateFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationHealthStateFilter" />
  <TypeSignature Language="F#" Value="type ApplicationHealthStateFilter = class" />
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
            フィルター処理<see cref="T:System.Fabric.Health.ApplicationHealthState" />オブジェクト。
            </summary>
    <remarks>エンティティのヘルス状態のチャンク クエリでは、粒度が細かいにアプリケーションのフィルターの一覧クエリ結果に含める必要があるアプリケーションの選択を指定できます。
            渡されたすべてのアプリケーションが、フィルターに関係なく、集計されたクラスターの正常性状態の評価に使用されることに注意してください。</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationHealthStateFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthStateFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:System.Fabric.Health.ApplicationHealthStateFilter" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationNameFilter">
      <MemberSignature Language="C#" Value="public Uri ApplicationNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateFilter.ApplicationNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationNameFilter As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationNameFilter : Uri with get, set" Usage="System.Fabric.Health.ApplicationHealthStateFilter.ApplicationNameFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアプリケーション名のフィルターを設定します。
            </summary>
        <value>アプリケーションの名前フィルター。</value>
        <remarks>指定した場合は、目的のアプリケーションにのみ、フィルターが適用されます。 フィルターに一致するアプリケーションで集計された正常性状態は、指定したヘルス状態のフィルターを一致しなければなりません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeNameFilter">
      <MemberSignature Language="C#" Value="public string ApplicationTypeNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateFilter.ApplicationTypeNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationTypeNameFilter As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeNameFilter : string with get, set" Usage="System.Fabric.Health.ApplicationHealthStateFilter.ApplicationTypeNameFilter" />
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
            取得またはアプリケーションの種類の名前フィルターを設定します。
            </summary>
        <value>アプリケーションの種類の名前のフィルター。</value>
        <remarks>指定した場合は、(特定のアプリケーション名) の具体的なフィルターがない型の指定したアプリケーションのすべてのアプリケーションに、フィルターが適用されます。
            フィルターに一致するアプリケーションは、集計された正常性状態は、指定したヘルス状態のフィルターを一致しなければなりません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedApplicationFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedApplicationHealthStateFilter&gt; DeployedApplicationFilters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.DeployedApplicationHealthStateFilter&gt; DeployedApplicationFilters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateFilter.DeployedApplicationFilters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedApplicationFilters As IList(Of DeployedApplicationHealthStateFilter)" />
      <MemberSignature Language="F#" Value="member this.DeployedApplicationFilters : System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedApplicationHealthStateFilter&gt;" Usage="System.Fabric.Health.ApplicationHealthStateFilter.DeployedApplicationFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedApplicationHealthStateFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            一覧を取得<see cref="T:System.Fabric.Health.DeployedApplicationHealthStateFilter" />を配置したアプリケーションの子の正常性状態に適用できます。
            </summary>
        <value>一連の<see cref="T:System.Fabric.Health.DeployedApplicationHealthStateFilter" />を配置したアプリケーションの子の正常性状態に適用できます。</value>
        <remarks>一覧には、展開されている 1 つの既定のアプリケーションのフィルターまたはクエリで返された粒度が細かいエンティティに特定の展開済みアプリケーションの展開済みアプリケーション フィルターを含めることができます。
            すべて展開、アプリケーション、アプリケーションの子としてフィルターに一致する子が返されます。
            空の場合、既定では子は返されません。</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.ApplicationHealthStateFilter.HealthStateFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthStateFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.ApplicationHealthState" />コレクション内のエントリ。 
            </summary>
        <value>集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.ApplicationHealthState" />コレクション内のエントリ。</value>
        <remarks>ヘルス状態フィルター値はメンバーまたはのメンバーのビットごとの組み合わせから取得<see cref="T:System.Fabric.Health.HealthStateFilter" />です。 フィルターに一致するアプリケーションは、集計された正常性状態は、指定したヘルス状態のフィルターを一致しなければなりません。
            ヘルス状態のフィルターが既定の場合は、特定のフィルター (アプリケーション名またはアプリケーションの種類名) が存在しない場合 [なし] に「ヘルス状態フィルターが既定値です。
            それ以外の場合、既定のフィルターはすべてに適用すると見なされます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.ServiceHealthStateFilter&gt; ServiceFilters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.ServiceHealthStateFilter&gt; ServiceFilters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateFilter.ServiceFilters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceFilters As IList(Of ServiceHealthStateFilter)" />
      <MemberSignature Language="F#" Value="member this.ServiceFilters : System.Collections.Generic.IList&lt;System.Fabric.Health.ServiceHealthStateFilter&gt;" Usage="System.Fabric.Health.ApplicationHealthStateFilter.ServiceFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.ServiceHealthStateFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            一覧を取得<see cref="T:System.Fabric.Health.ServiceHealthStateFilter" />をサービスの子の正常性状態に適用できます。
            </summary>
        <value>一連の<see cref="T:System.Fabric.Health.ServiceHealthStateFilter" />をサービスの子の正常性状態に適用できます。</value>
        <remarks>一覧には、1 つの既定のサービス フィルターまたはクエリで返された粒度が細かいエンティティに特定のサービスのサービスのフィルターを含めることができます。
            フィルターに一致するすべてのサービスの子は、アプリケーションの子として返されます。
            空の場合、既定では子は返されません。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthStateFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationHealthStateFilter.ToString " />
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
            フィルターの文字列表現を返します。
            </summary>
        <returns>フィルターの文字列形式。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>