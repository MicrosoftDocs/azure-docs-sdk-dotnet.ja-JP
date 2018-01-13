<Type Name="CloudAnalyticsClient" FullName="Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient">
  <TypeSignature Language="C#" Value="public sealed class CloudAnalyticsClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CloudAnalyticsClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CloudAnalyticsClient" />
  <TypeSignature Language="F#" Value="type CloudAnalyticsClient = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Microsoft Azure Storage Analytics のクライアント側の論理表現を提供します。 このクライアントを使用してを構成および記憶域の分析に対する要求を実行します。
            </summary>
    <remarks>分析サービス クライアントは、Blob およびテーブル サービスのエンドポイントをカプセル化します。 また、ストレージ アカウントにアクセスするための資格情報をカプセル化します。</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudAnalyticsClient (Microsoft.WindowsAzure.Storage.StorageUri blobStorageUri, Microsoft.WindowsAzure.Storage.StorageUri tableStorageUri, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.StorageUri blobStorageUri, class Microsoft.WindowsAzure.Storage.StorageUri tableStorageUri, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.#ctor(Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobStorageUri As StorageUri, tableStorageUri As StorageUri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient" Usage="new Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient (blobStorageUri, tableStorageUri, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="blobStorageUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="tableStorageUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="blobStorageUri">A<see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />を使用してクライアントを作成する Blob サービス エンドポイントを表すオブジェクト。</param>
        <param name="tableStorageUri">A<see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />を使用してクライアントを作成するテーブル サービスのエンドポイントを含むオブジェクト。</param>
        <param name="credentials"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient" />クラスの指定した Blob およびテーブル サービスのエンドポイントを使用して、アカウントの資格情報。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCapacityQuery">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity&gt; CreateCapacityQuery ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity&gt; CreateCapacityQuery() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.CreateCapacityQuery" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCapacityQuery () As TableQuery(Of CapacityEntity)" />
      <MemberSignature Language="F#" Value="member this.CreateCapacityQuery : unit -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity&gt;" Usage="cloudAnalyticsClient.CreateCapacityQuery " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            作成、 <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> Blob サービスの容量テーブルを照会するためのオブジェクト。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> オブジェクト。</returns>
        <remarks>このメソッドは、Blob サービスにのみ適用されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateHourMetricsQuery">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt; CreateHourMetricsQuery (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, Microsoft.WindowsAzure.Storage.StorageLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt; CreateHourMetricsQuery(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype Microsoft.WindowsAzure.Storage.StorageLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.CreateHourMetricsQuery(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,Microsoft.WindowsAzure.Storage.StorageLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateHourMetricsQuery (service As StorageService, location As StorageLocation) As TableQuery(Of MetricsEntity)" />
      <MemberSignature Language="F#" Value="member this.CreateHourMetricsQuery : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * Microsoft.WindowsAzure.Storage.StorageLocation -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt;" Usage="cloudAnalyticsClient.CreateHourMetricsQuery (service, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="location" Type="Microsoft.WindowsAzure.Storage.StorageLocation" />
      </Parameters>
      <Docs>
        <param name="service"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</param>
        <param name="location"><see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" /> 列挙値。</param>
        <summary>
            作成、<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />時間単位のメトリック ログ テーブルを照会するためのオブジェクト。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMinuteMetricsQuery">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt; CreateMinuteMetricsQuery (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, Microsoft.WindowsAzure.Storage.StorageLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt; CreateMinuteMetricsQuery(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype Microsoft.WindowsAzure.Storage.StorageLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.CreateMinuteMetricsQuery(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,Microsoft.WindowsAzure.Storage.StorageLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMinuteMetricsQuery (service As StorageService, location As StorageLocation) As TableQuery(Of MetricsEntity)" />
      <MemberSignature Language="F#" Value="member this.CreateMinuteMetricsQuery : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * Microsoft.WindowsAzure.Storage.StorageLocation -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt;" Usage="cloudAnalyticsClient.CreateMinuteMetricsQuery (service, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="location" Type="Microsoft.WindowsAzure.Storage.StorageLocation" />
      </Parameters>
      <Docs>
        <param name="service"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</param>
        <param name="location"><see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" /> 列挙値。</param>
        <summary>
            作成、<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />分単位のメトリック ログ テーブルを照会するためのオブジェクト。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCapacityTable">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.CloudTable GetCapacityTable ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.CloudTable GetCapacityTable() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.GetCapacityTable" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCapacityTable () As CloudTable" />
      <MemberSignature Language="F#" Value="member this.GetCapacityTable : unit -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTable" Usage="cloudAnalyticsClient.GetCapacityTable " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.CloudTable</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Blob サービスの容量メトリック テーブルを取得します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHourMetricsTable">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.CloudTable GetHourMetricsTable (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.CloudTable GetHourMetricsTable(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.GetHourMetricsTable(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetHourMetricsTable (service As StorageService) As CloudTable" />
      <MemberSignature Language="F#" Value="member this.GetHourMetricsTable : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTable" Usage="cloudAnalyticsClient.GetHourMetricsTable service" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.CloudTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
      </Parameters>
      <Docs>
        <param name="service"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</param>
        <summary>
            指定した記憶域サービスの時間単位のメトリックのテーブルを取得します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHourMetricsTable">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.CloudTable GetHourMetricsTable (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, Microsoft.WindowsAzure.Storage.StorageLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.CloudTable GetHourMetricsTable(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype Microsoft.WindowsAzure.Storage.StorageLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.GetHourMetricsTable(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,Microsoft.WindowsAzure.Storage.StorageLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetHourMetricsTable (service As StorageService, location As StorageLocation) As CloudTable" />
      <MemberSignature Language="F#" Value="member this.GetHourMetricsTable : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * Microsoft.WindowsAzure.Storage.StorageLocation -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTable" Usage="cloudAnalyticsClient.GetHourMetricsTable (service, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.CloudTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="location" Type="Microsoft.WindowsAzure.Storage.StorageLocation" />
      </Parameters>
      <Docs>
        <param name="service"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</param>
        <param name="location"><see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" /> 列挙値。</param>
        <summary>
            指定した記憶域サービスの時間単位のメトリックのテーブルを取得します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLogDirectory">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory GetLogDirectory (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory GetLogDirectory(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.GetLogDirectory(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetLogDirectory (service As StorageService) As CloudBlobDirectory" />
      <MemberSignature Language="F#" Value="member this.GetLogDirectory : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" Usage="cloudAnalyticsClient.GetLogDirectory service" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
      </Parameters>
      <Docs>
        <param name="service"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</param>
        <summary>
            取得、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />を指定した記憶域サービスのログを含むオブジェクト。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMinuteMetricsTable">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.CloudTable GetMinuteMetricsTable (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.CloudTable GetMinuteMetricsTable(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.GetMinuteMetricsTable(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMinuteMetricsTable (service As StorageService) As CloudTable" />
      <MemberSignature Language="F#" Value="member this.GetMinuteMetricsTable : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTable" Usage="cloudAnalyticsClient.GetMinuteMetricsTable service" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.CloudTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
      </Parameters>
      <Docs>
        <param name="service"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</param>
        <summary>
            指定した記憶域サービスの分単位のメトリックのテーブルを取得します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMinuteMetricsTable">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.CloudTable GetMinuteMetricsTable (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, Microsoft.WindowsAzure.Storage.StorageLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.CloudTable GetMinuteMetricsTable(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype Microsoft.WindowsAzure.Storage.StorageLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.GetMinuteMetricsTable(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,Microsoft.WindowsAzure.Storage.StorageLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMinuteMetricsTable (service As StorageService, location As StorageLocation) As CloudTable" />
      <MemberSignature Language="F#" Value="member this.GetMinuteMetricsTable : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * Microsoft.WindowsAzure.Storage.StorageLocation -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTable" Usage="cloudAnalyticsClient.GetMinuteMetricsTable (service, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.CloudTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="location" Type="Microsoft.WindowsAzure.Storage.StorageLocation" />
      </Parameters>
      <Docs>
        <param name="service"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</param>
        <param name="location"><see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" /> 列挙値。</param>
        <summary>
            指定した記憶域サービスの分単位のメトリックのテーブルを取得します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogRecords(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListLogRecords (service As StorageService) As IEnumerable(Of LogRecord)" />
      <MemberSignature Language="F#" Value="member this.ListLogRecords : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;" Usage="cloudAnalyticsClient.ListLogRecords service" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
      </Parameters>
      <Docs>
        <param name="service"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</param>
        <summary>
            遅延を取得、分析のログ レコードの列挙可能なコレクションを返します。
            </summary>
        <returns>実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" />遅れてが取得されます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogRecords(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.ListLogRecords : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;" Usage="cloudAnalyticsClient.ListLogRecords (service, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="service"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            遅延を取得、分析のログ レコードの列挙可能なコレクションを返します。
            </summary>
        <returns>実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" />遅れてが取得されます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, DateTimeOffset startTime, Nullable&lt;DateTimeOffset&gt; endTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype System.DateTimeOffset startTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogRecords(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,System.DateTimeOffset,System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="Public Function ListLogRecords (service As StorageService, startTime As DateTimeOffset, endTime As Nullable(Of DateTimeOffset)) As IEnumerable(Of LogRecord)" />
      <MemberSignature Language="F#" Value="member this.ListLogRecords : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * DateTimeOffset * Nullable&lt;DateTimeOffset&gt; -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;" Usage="cloudAnalyticsClient.ListLogRecords (service, startTime, endTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="startTime" Type="System.DateTimeOffset" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="service"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</param>
        <param name="startTime">A<see cref="T:System.DateTimeOffset" />ログを取得する時間の範囲の開始を表すオブジェクト。</param>
        <param name="endTime">A<see cref="T:System.DateTimeOffset" />ログを取得する時間の範囲の終わりを表すオブジェクト。</param>
        <summary>
            遅延を取得、分析のログ レコードの列挙可能なコレクションを返します。
            </summary>
        <returns>実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" />遅れてが取得されます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, DateTimeOffset startTime, Nullable&lt;DateTimeOffset&gt; endTime, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype System.DateTimeOffset startTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endTime, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogRecords(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,System.DateTimeOffset,System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.ListLogRecords : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * DateTimeOffset * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;" Usage="cloudAnalyticsClient.ListLogRecords (service, startTime, endTime, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="startTime" Type="System.DateTimeOffset" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="service"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</param>
        <param name="startTime">A<see cref="T:System.DateTimeOffset" />ログを取得する時間の範囲の開始を表すオブジェクト。</param>
        <param name="endTime">A<see cref="T:System.DateTimeOffset" />ログを取得する時間の範囲の終わりを表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            遅延を取得、分析のログ レコードの列挙可能なコレクションを返します。
            </summary>
        <returns>実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" />遅れてが取得されます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogs(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListLogs (service As StorageService) As IEnumerable(Of ICloudBlob)" />
      <MemberSignature Language="F#" Value="member this.ListLogs : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" Usage="cloudAnalyticsClient.ListLogs service" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
      </Parameters>
      <Docs>
        <param name="service"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</param>
        <summary>
            分析ログ レコードを含むログ blob の列挙可能なコレクションを返します。 遅延は、blob を取得します。
            </summary>
        <returns>実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" />遅れてが取得されます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, DateTimeOffset startTime, Nullable&lt;DateTimeOffset&gt; endTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype System.DateTimeOffset startTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogs(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,System.DateTimeOffset,System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="Public Function ListLogs (service As StorageService, startTime As DateTimeOffset, endTime As Nullable(Of DateTimeOffset)) As IEnumerable(Of ICloudBlob)" />
      <MemberSignature Language="F#" Value="member this.ListLogs : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * DateTimeOffset * Nullable&lt;DateTimeOffset&gt; -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" Usage="cloudAnalyticsClient.ListLogs (service, startTime, endTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="startTime" Type="System.DateTimeOffset" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="service"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</param>
        <param name="startTime">A<see cref="T:System.DateTimeOffset" />ログの取得の開始時刻を表すオブジェクト。</param>
        <param name="endTime">A<see cref="T:System.DateTimeOffset" />ログの取得の終了時刻を表すオブジェクト。</param>
        <summary>
            分析ログ レコードを含むログ blob の列挙可能なコレクションを返します。 遅延は、blob を取得します。
            </summary>
        <returns>実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" />遅れてが取得されます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations operations, Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails details, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations operations, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails details, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogs(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations,Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.ListLogs : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" Usage="cloudAnalyticsClient.ListLogs (service, operations, details, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations" />
        <Parameter Name="details" Type="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="service"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</param>
        <param name="operations">A<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations" />ログ blob をフィルター処理するログ記録操作の種類を示す列挙値。</param>
        <param name="details">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> blob のメタデータを返す必要があるかどうかを示す列挙値。 のみ<c>None</c>と<c>メタデータ</c>は有効な値です。 </param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            分析ログ レコードを含むログ blob の列挙可能なコレクションを返します。 遅延は、blob を取得します。
            </summary>
        <returns>実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" />遅れてが取得されます。</returns>
        <remarks>ログ記録操作を指定するが入力したメモ、<paramref name="operations" />パラメーターで指定されたログ記録操作を含む任意の分析ログ blob が返される場合、場合でも、そのログ blob には、その他の種類のログ記録操作も含まれています。 現在サポートされている唯一メモは値を<paramref name="details" />パラメーターは<c>None</c>と<c>メタデータ</c>です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, DateTimeOffset startTime, Nullable&lt;DateTimeOffset&gt; endTime, Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations operations, Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails details, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype System.DateTimeOffset startTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endTime, valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations operations, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails details, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogs(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,System.DateTimeOffset,System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations,Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.ListLogs : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * DateTimeOffset * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" Usage="cloudAnalyticsClient.ListLogs (service, startTime, endTime, operations, details, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="startTime" Type="System.DateTimeOffset" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations" />
        <Parameter Name="details" Type="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="service"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" /> 列挙値。</param>
        <param name="startTime">A<see cref="T:System.DateTimeOffset" />ログを取得する時間の範囲の開始を表すオブジェクト。</param>
        <param name="endTime">A<see cref="T:System.DateTimeOffset" />ログを取得する時間の範囲の終わりを表すオブジェクト。</param>
        <param name="operations">A<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations" />ログ blob をフィルター処理するログ記録操作の種類を示す列挙値。</param>
        <param name="details">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> blob のメタデータを返す必要があるかどうかを示す列挙値。 のみ<c>None</c>と<c>メタデータ</c>は有効な値です。 </param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            分析ログ レコードを含むログ blob の列挙可能なコレクションを返します。 遅延は、blob を取得します。
            </summary>
        <returns>実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" />遅れてが取得されます。</returns>
        <remarks>ログ記録操作を指定するが入力したメモ、<paramref name="operations" />パラメーターで指定されたログ記録操作を含む任意の分析ログ blob が返される場合、場合でも、そのログ blob には、その他の種類のログ記録操作も含まれています。 現在サポートされている唯一メモは値を<paramref name="details" />パラメーターは<c>None</c>と<c>メタデータ</c>です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseLogBlob">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ParseLogBlob (Microsoft.WindowsAzure.Storage.Blob.ICloudBlob logBlob);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ParseLogBlob(class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob logBlob) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ParseLogBlob(Microsoft.WindowsAzure.Storage.Blob.ICloudBlob)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ParseLogBlob (logBlob As ICloudBlob) As IEnumerable(Of LogRecord)" />
      <MemberSignature Language="F#" Value="static member ParseLogBlob : Microsoft.WindowsAzure.Storage.Blob.ICloudBlob -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ParseLogBlob logBlob" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="logBlob" Type="Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" />
      </Parameters>
      <Docs>
        <param name="logBlob"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" />ログ レコードを解析する対象のオブジェクト。</param>
        <summary>
            遅延を取得、分析のログ レコードの列挙可能なコレクションを返します。
            </summary>
        <returns>実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" />遅れてが取得されます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseLogBlobs">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ParseLogBlobs (System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; logBlobs);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ParseLogBlobs(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; logBlobs) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ParseLogBlobs(System.Collections.Generic.IEnumerable{Microsoft.WindowsAzure.Storage.Blob.ICloudBlob})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ParseLogBlobs (logBlobs As IEnumerable(Of ICloudBlob)) As IEnumerable(Of LogRecord)" />
      <MemberSignature Language="F#" Value="static member ParseLogBlobs : seq&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ParseLogBlobs logBlobs" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="logBlobs" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" />
      </Parameters>
      <Docs>
        <param name="logBlobs">列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" />ログ レコードを解析するオブジェクト。</param>
        <summary>
            遅延を取得、分析のログ レコードの列挙可能なコレクションを返します。
            </summary>
        <returns>実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" />遅れてが取得されます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseLogStream">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ParseLogStream (System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ParseLogStream(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ParseLogStream(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="static member ParseLogStream : System.IO.Stream -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ParseLogStream stream" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="stream"><see cref="T:System.IO.Stream" />ログ レコードを解析する対象のオブジェクト。</param>
        <summary>
            遅延を取得、分析のログ レコードの列挙可能なコレクションを返します。
            </summary>
        <returns>実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" />遅れてが取得されます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>