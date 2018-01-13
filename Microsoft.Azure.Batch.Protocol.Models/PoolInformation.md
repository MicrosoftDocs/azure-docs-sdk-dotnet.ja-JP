<Type Name="PoolInformation" FullName="Microsoft.Azure.Batch.Protocol.Models.PoolInformation">
  <TypeSignature Language="C#" Value="public class PoolInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.PoolInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolInformation" />
  <TypeSignature Language="F#" Value="type PoolInformation = class" />
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
            ジョブのプールに割り当て方法を指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            PoolInformation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolInformation (string poolId = null, Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification autoPoolSpecification = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string poolId, class Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification autoPoolSpecification) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolInformation.#ctor(System.String,Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.PoolInformation : string * Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolInformation" Usage="new Microsoft.Azure.Batch.Protocol.Models.PoolInformation (poolId, autoPoolSpecification)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="autoPoolSpecification" Type="Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification" />
      </Parameters>
      <Docs>
        <param name="poolId">既存のプールの ID。 ジョブのすべてのタスクは、指定されたプールで実行されます。</param>
        <param name="autoPoolSpecification">一時 '自動プール' の項目の特性。 ジョブが送信されるときに、バッチ サービスはこの自動プールを作成します。</param>
        <summary>
            PoolInformation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoPoolSpecification">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification AutoPoolSpecification { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification AutoPoolSpecification" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolInformation.AutoPoolSpecification" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoPoolSpecification As AutoPoolSpecification" />
      <MemberSignature Language="F#" Value="member this.AutoPoolSpecification : Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolInformation.AutoPoolSpecification" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoPoolSpecification")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または一時的な '自動プール' の特性を設定します。 ジョブが送信されるときに、バッチ サービスはこの自動プールを作成します。
            </summary>
        <value>To be added.</value>
        <remarks>
            自動プールの作成に失敗した場合は、バッチ サービスは、完了済みの状態にジョブを移動され、プールの作成エラーがジョブのスケジュール エラーのプロパティで設定されます。 バッチ サービスは、有効期間を管理 (両方を作成して、keepAlive が指定されていない場合、削除)、自動プールのです。 ジョブがアクティブなときに、自動プールの有効期間に影響を与えるユーザーの操作は、予期しない動作になります。
            プールの ID と自動プールの仕様の両方ではなくはどちらかを指定する必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolId">
      <MemberSignature Language="C#" Value="public string PoolId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PoolId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolInformation.PoolId" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolId As String" />
      <MemberSignature Language="F#" Value="member this.PoolId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolInformation.PoolId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="poolId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または既存のプールの ID を設定します。 ジョブのすべてのタスクは、指定されたプールで実行されます。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティによって参照されるプールが存在することを確認する必要があります。
            プールは存在しない場合、Batch service はジョブをスケジュールしようとして 時に、その id のプールを作成するまで、ジョブのタスクは実行されません。ジョブ要求; が、バッチ サービスで拒否されましていないことに注意してください。これは単にタスクが実行されない、プールが存在するまでです。
            プールの ID と自動プールの仕様の両方ではなくはどちらかを指定する必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolInformation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="poolInformation.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>