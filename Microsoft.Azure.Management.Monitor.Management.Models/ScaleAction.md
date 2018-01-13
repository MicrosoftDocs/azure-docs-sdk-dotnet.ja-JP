<Type Name="ScaleAction" FullName="Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction">
  <TypeSignature Language="C#" Value="public class ScaleAction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ScaleAction extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction" />
  <TypeSignature Language="VB.NET" Value="Public Class ScaleAction" />
  <TypeSignature Language="F#" Value="type ScaleAction = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            スケーリング処理のパラメーターです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScaleAction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ScaleAction クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScaleAction (Microsoft.Azure.Management.Monitor.Management.Models.ScaleDirection direction, Microsoft.Azure.Management.Monitor.Management.Models.ScaleType type, TimeSpan cooldown, string value = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Monitor.Management.Models.ScaleDirection direction, valuetype Microsoft.Azure.Management.Monitor.Management.Models.ScaleType type, valuetype System.TimeSpan cooldown, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction.#ctor(Microsoft.Azure.Management.Monitor.Management.Models.ScaleDirection,Microsoft.Azure.Management.Monitor.Management.Models.ScaleType,System.TimeSpan,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (direction As ScaleDirection, type As ScaleType, cooldown As TimeSpan, Optional value As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction : Microsoft.Azure.Management.Monitor.Management.Models.ScaleDirection * Microsoft.Azure.Management.Monitor.Management.Models.ScaleType * TimeSpan * string -&gt; Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction (direction, type, cooldown, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="direction" Type="Microsoft.Azure.Management.Monitor.Management.Models.ScaleDirection" />
        <Parameter Name="type" Type="Microsoft.Azure.Management.Monitor.Management.Models.ScaleType" />
        <Parameter Name="cooldown" Type="System.TimeSpan" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="direction">スケールの方向。 かどうかスケーリング処理を増減しますインスタンスの数。 使用可能な値が含まれます 'None'、'拡大'、'縮小'。</param>
        <param name="type">スケール規則が発生したときに実行するアクションの種類。 使用可能な値が含まれます: 'ChangeCount'、'PercentChangeCount'、'ExactCount'</param>
        <param name="cooldown">このアクションが発生する前に、最後のスケーリング処理されてから待機する時間の量。 1 週間から 1 分 ISO 8601 形式である必要がある必要があります。</param>
        <param name="value">スケーリング処理で使用されるインスタンスの数。 1 以上の値を設定する必要があります。 既定値は 1 です。</param>
        <summary>
            ScaleAction クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Cooldown">
      <MemberSignature Language="C#" Value="public TimeSpan Cooldown { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan Cooldown" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction.Cooldown" />
      <MemberSignature Language="VB.NET" Value="Public Property Cooldown As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.Cooldown : TimeSpan with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction.Cooldown" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cooldown")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこの操作が行われる前に、最後のスケーリング処理されてから待機する時間を設定します。 1 週間から 1 分 ISO 8601 形式である必要がある必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Direction">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.ScaleDirection Direction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Monitor.Management.Models.ScaleDirection Direction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction.Direction" />
      <MemberSignature Language="VB.NET" Value="Public Property Direction As ScaleDirection" />
      <MemberSignature Language="F#" Value="member this.Direction : Microsoft.Azure.Management.Monitor.Management.Models.ScaleDirection with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction.Direction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="direction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.ScaleDirection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはスケール方向を設定します。 かどうかスケーリング処理を増減しますインスタンスの数。 使用可能な値が含まれます 'None'、'拡大'、'縮小'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.ScaleType Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Monitor.Management.Models.ScaleType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As ScaleType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.Management.Monitor.Management.Models.ScaleType with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.ScaleType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはスケール規則が発生したときに実行するアクションの種類を設定します。 使用可能な値が含まれます: 'ChangeCount'、'PercentChangeCount'、'ExactCount'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="scaleAction.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
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
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはスケーリング処理で使用されるインスタンスの数を設定します。 1 以上の値を設定する必要があります。 既定値は 1 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>