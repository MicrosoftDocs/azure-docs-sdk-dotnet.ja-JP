<Type Name="IRequestOptions" FullName="Microsoft.WindowsAzure.Storage.IRequestOptions">
  <TypeSignature Language="C#" Value="public interface IRequestOptions" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRequestOptions" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.IRequestOptions" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRequestOptions" />
  <TypeSignature Language="F#" Value="type IRequestOptions = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            要求のオプションの種類に必要なインターフェイスです。
            </summary>
    <remarks><see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />、 <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />、および<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />クラスで実装、<see cref="T:Microsoft.WindowsAzure.Storage.IRequestOptions" />インターフェイスです。</remarks>
  </Docs>
  <Members>
    <Member MemberName="LocationMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt; LocationMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt; LocationMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.IRequestOptions.LocationMode" />
      <MemberSignature Language="VB.NET" Value="Public Property LocationMode As Nullable(Of LocationMode)" />
      <MemberSignature Language="F#" Value="member this.LocationMode : Nullable&lt;Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.IRequestOptions.LocationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または要求の配置モードを設定します。
            </summary>
        <value><see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode" /> 列挙値。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumExecutionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; MaximumExecutionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; MaximumExecutionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.IRequestOptions.MaximumExecutionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaximumExecutionTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.MaximumExecutionTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.IRequestOptions.MaximumExecutionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはすべての潜在的な再試行の最大実行時間を設定します。
            </summary>
        <value>A<see cref="T:System.TimeSpan" />すべて潜在的な再試行の最大実行時間を格納しています。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequireEncryption">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequireEncryption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequireEncryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.IRequestOptions.RequireEncryption" />
      <MemberSignature Language="VB.NET" Value="Public Property RequireEncryption As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequireEncryption : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.IRequestOptions.RequireEncryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはクライアント ライブラリによって読み取りし、書き込みのデータを暗号化するかどうかを示す値を設定します。
            </summary>
        <value>使用して<c>true</c>すべてのトランザクションの暗号化/暗号化解除、それ以外のデータがする必要がありますを指定する<c>false</c>です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy RetryPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy RetryPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.IRequestOptions.RetryPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryPolicy As IRetryPolicy" />
      <MemberSignature Language="F#" Value="member this.RetryPolicy : Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy with get, set" Usage="Microsoft.WindowsAzure.Storage.IRequestOptions.RetryPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または要求の再試行ポリシーを設定します。
            </summary>
        <value><see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" /> 型のオブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ServerTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ServerTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.IRequestOptions.ServerTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ServerTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.IRequestOptions.ServerTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または要求の既定のサーバー タイムアウトを設定します。
            </summary>
        <value>A<see cref="T:System.TimeSpan" />サーバー タイムアウト間隔を表すです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>