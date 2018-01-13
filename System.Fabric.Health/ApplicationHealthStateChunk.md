<Type Name="ApplicationHealthStateChunk" FullName="System.Fabric.Health.ApplicationHealthStateChunk">
  <TypeSignature Language="C#" Value="public sealed class ApplicationHealthStateChunk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationHealthStateChunk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ApplicationHealthStateChunk" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationHealthStateChunk" />
  <TypeSignature Language="F#" Value="type ApplicationHealthStateChunk = class" />
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
            チャンクを表して、アプリケーション ヘルス状態、アプリケーションに関する基本的な正常性の情報が含まれています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateChunk.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Health.ApplicationHealthStateChunk.ApplicationName" />
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
            アプリケーションの名前を取得します。
            </summary>
        <value>アプリケーション名。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeName">
      <MemberSignature Language="C#" Value="public string ApplicationTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateChunk.ApplicationTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeName : string" Usage="System.Fabric.Health.ApplicationHealthStateChunk.ApplicationTypeName" />
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
            アプリケーションの種類名を取得します。
            </summary>
        <value>アプリケーションの種類名です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedApplicationHealthStateChunks">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.DeployedApplicationHealthStateChunkList DeployedApplicationHealthStateChunks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.DeployedApplicationHealthStateChunkList DeployedApplicationHealthStateChunks" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateChunk.DeployedApplicationHealthStateChunks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedApplicationHealthStateChunks As DeployedApplicationHealthStateChunkList" />
      <MemberSignature Language="F#" Value="member this.DeployedApplicationHealthStateChunks : System.Fabric.Health.DeployedApplicationHealthStateChunkList" Usage="System.Fabric.Health.ApplicationHealthStateChunk.DeployedApplicationHealthStateChunks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.DeployedApplicationHealthStateChunkList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            入力のフィルターを適用する展開済みアプリケーション ヘルス状態のチャンクの一覧を取得します。
            </summary>
        <value>入力のフィルターを適用する展開済みアプリケーション ヘルス状態のチャンクの一覧。</value>
        <remarks>
          <para>既定では、子ない結果に含められます。 ユーザーは、必要な正常性アドインまたはその他の情報に基づく子の一部を含めるように要求できます。 たとえば、ユーザーは、以下のヘルス状態のエラーのある展開済みのすべてのアプリケーションを要求できます。
            フィルター値に関係なく、すべての子は、アプリケーションで集計された正常性が計算に使用されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateChunk.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Health.ApplicationHealthStateChunk.HealthState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            報告された状態のすべてのイベント、子、およびアプリケーションの正常性ポリシーに基づくアプリケーション ヘルス状態は、計算を集計する取得します。
            </summary>
        <value>アプリケーションでは、ヘルス状態を集計します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceHealthStateChunks">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ServiceHealthStateChunkList ServiceHealthStateChunks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ServiceHealthStateChunkList ServiceHealthStateChunks" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateChunk.ServiceHealthStateChunks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceHealthStateChunks As ServiceHealthStateChunkList" />
      <MemberSignature Language="F#" Value="member this.ServiceHealthStateChunks : System.Fabric.Health.ServiceHealthStateChunkList" Usage="System.Fabric.Health.ApplicationHealthStateChunk.ServiceHealthStateChunks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ServiceHealthStateChunkList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービスのヘルス状態の一覧に、入力フィルターを尊重状態チャンクを取得します。
            </summary>
        <value>入力フィルターを適用するサービスのヘルス状態のチャンクの一覧。</value>
        <remarks>
          <para>既定では、子ない結果に含められます。 ユーザーは、必要な正常性アドインまたはその他の情報に基づく子の一部を含めるように要求できます。 たとえば、ユーザーは、ヘルス状態のエラーのあるすべてのサービスを指定する要求できます。
            フィルター値に関係なく、すべての子は、アプリケーションで集計された正常性が計算に使用されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthStateChunk.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationHealthStateChunk.ToString " />
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
            ヘルス状態のチャンクについて説明する文字列を作成します。
            </summary>
        <returns>ヘルス状態のチャンクの説明の文字列を指定します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>