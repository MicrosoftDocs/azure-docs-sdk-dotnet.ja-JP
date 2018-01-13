<Type Name="ScaleSettings" FullName="Microsoft.Azure.Management.Batch.Models.ScaleSettings">
  <TypeSignature Language="C#" Value="public class ScaleSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ScaleSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.ScaleSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class ScaleSettings" />
  <TypeSignature Language="F#" Value="type ScaleSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            プールのスケール設定
            </summary>
    <remarks>
            プールの目的のサイズを定義します。 要求された targetDedicatedNodes が指定されている ' fixedScale' または 'autoScale' を定期的に再評価する式を定義を指定できます。 このプロパティが指定されていない場合、プールに 0 targetDedicatedNodes と固定小数点以下桁数があります。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScaleSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ScaleSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ScaleSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScaleSettings (Microsoft.Azure.Management.Batch.Models.FixedScaleSettings fixedScale = null, Microsoft.Azure.Management.Batch.Models.AutoScaleSettings autoScale = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Batch.Models.FixedScaleSettings fixedScale, class Microsoft.Azure.Management.Batch.Models.AutoScaleSettings autoScale) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ScaleSettings.#ctor(Microsoft.Azure.Management.Batch.Models.FixedScaleSettings,Microsoft.Azure.Management.Batch.Models.AutoScaleSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional fixedScale As FixedScaleSettings = null, Optional autoScale As AutoScaleSettings = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.ScaleSettings : Microsoft.Azure.Management.Batch.Models.FixedScaleSettings * Microsoft.Azure.Management.Batch.Models.AutoScaleSettings -&gt; Microsoft.Azure.Management.Batch.Models.ScaleSettings" Usage="new Microsoft.Azure.Management.Batch.Models.ScaleSettings (fixedScale, autoScale)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="fixedScale" Type="Microsoft.Azure.Management.Batch.Models.FixedScaleSettings" />
        <Parameter Name="autoScale" Type="Microsoft.Azure.Management.Batch.Models.AutoScaleSettings" />
      </Parameters>
      <Docs>
        <param name="fixedScale">プールのスケール設定を固定します。</param>
        <param name="autoScale">プールの自動スケール設定します。</param>
        <summary>
            ScaleSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScale">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.AutoScaleSettings AutoScale { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.AutoScaleSettings AutoScale" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ScaleSettings.AutoScale" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScale As AutoScaleSettings" />
      <MemberSignature Language="F#" Value="member this.AutoScale : Microsoft.Azure.Management.Batch.Models.AutoScaleSettings with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ScaleSettings.AutoScale" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoScale")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.AutoScaleSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプールの自動スケール設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティと fixedScale は相互に排他的とプロパティのいずれかを指定する必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FixedScale">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.FixedScaleSettings FixedScale { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.FixedScaleSettings FixedScale" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ScaleSettings.FixedScale" />
      <MemberSignature Language="VB.NET" Value="Public Property FixedScale As FixedScaleSettings" />
      <MemberSignature Language="F#" Value="member this.FixedScale : Microsoft.Azure.Management.Batch.Models.FixedScaleSettings with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ScaleSettings.FixedScale" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fixedScale")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.FixedScaleSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプールの固定のスケール設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティと自動スケールでは、相互に排他的とプロパティのいずれかを指定する必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ScaleSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="scaleSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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